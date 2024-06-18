# PRO-E4_SUBTOTAL_OPERATORS

Query 1: Sales Order Shipments by Month and Category Code1

Write an SQL statement to display the sum of the extended cost and the sum of the quantity. The results should include data for shipments (transaction type 5) in calendar year 2011. Summarize the result by calendar month and Address Category Code 1. The result should include the grouped columns and the full totals for every combination of grouped columns. Do not use the GROUPING SETS and UNION operators.


<img width="860" alt="Screenshot 2024-06-18 at 3 08 26 PM" src="https://github.com/harbeyme24/PRO-E4_SUBTOTAL_OPERATORS/assets/143273418/8a2a7ba6-9f81-486f-a2ef-36ada2979cff">

Query 2: Sales Order Shipments by Name, Zip, and Quarter

Write an SQL statement to display the sum of the extended cost and the number of inventory transactions. The results should include data for shipments (transaction type 5) in calendar years 2011 and 2012. Summarize the result by calendar quarter, customer zip code, and customer name. The result should include the grouped columns and full set of subtotals for every combination of grouped columns. Do not use the CUBE and UNION operators.

<img width="1710" alt="Screenshot 2024-06-18 at 3 28 55 PM" src="https://github.com/harbeyme24/PRO-E4_SUBTOTAL_OPERATORS/assets/143273418/dd24f1cf-c443-48e2-94de-95e3ab34171d">

Query 3: Transfers by Company and Branch Plant

Write an SQL statement to display the sum of the extended cost and the sum of the quantity. The results should include data for transfers (transaction type 2). Summarize the result by company name and branch plant name. The result should include the grouped columns and a partial set of subtotals in order of the grouped columns (company name and branch plant name). Transfer quantities by design should sum to zero across all companies so that the grand total should be 0 for the sum of quantity and extended cost. Do not use the GROUPING SETS and UNION operators.


<img width="1321" alt="Screenshot 2024-06-18 at 3 43 49 PM" src="https://github.com/harbeyme24/PRO-E4_SUBTOTAL_OPERATORS/assets/143273418/c9781b89-6cff-440b-8b5a-f8f693b61560">


Query 4: Inventory Transactions by Transaction Description, Company, and Branch Plant

Write an SQL statement to display the sum of the extended cost and the number of inventory transactions. The results should include data for all transaction types. Summarize the result by transaction description, company name, and branch plant name. The result should include the grouped columns and partial totals in order of the grouped columns (transaction description, company name, and branch plant name). Do not use the ROLLUP and UNION operators.

<img width="1311" alt="Screenshot 2024-06-18 at 4 23 51 PM" src="https://github.com/harbeyme24/PRO-E4_SUBTOTAL_OPERATORS/assets/143273418/d821beb0-beb6-4ca3-9be1-32779bc4b879">


Query 5: Adjustments by Part Number

Write an SQL statement to display the sum of the extended cost and the number of inventory transactions. The results should include data for shipments (transaction type 5) in calendar years 2011 and 2012. Summarize the result by calendar year, calendar quarter, and customer name. The result should show the grouped columns and the normal set of group by results plus partial subtotals for year and quarter concatenated with customer name.  Do not use the GROUPING SETS and UNION operators. (Hint: see the partial ROLLUP example in lesson 4).


![Uploading Screenshot 2024-06-18 at 4.40.01 PM.png…]()





