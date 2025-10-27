This project uses AdventureWorks data to link customer purchases to the store's inventory.
It uses data from employees, customers, vendors, products, purchase orders, and sales orders.
I used the process below to create this new data warehouse. 

Step 1: Set up a connection between the MySQL Adventureworks database and MongoDB.
Step 2: Populated MongoDB with source data and json files downloaded from Adventureworks.
Step 3: Created and populated dimension tables (employees, customers, products, vendors).
Step 4: Transform the data frames, as needed -- reformatting dates, inserting keys, and dropping columns with nulls.
Step 5: Loaded the data frames into the new data warehouse.
Step 6: Created and populated fact tables (fact_purchase_orders, fact_sales_orders). 
Step 7: Transform the data frames, as needed -- reformatting dates and inserting keys.
Step 8: Find the primary keys from the dimension tables.
Step 9: Merging fact tables with dimension tables, using their primary keys. Insert new primary keys for the fact tables.
Step 10: Loaded the fact table data frames into the new data warehouse.
Step 11: Use SQL to demonstrate that the new Adventureworks dataset works and contains the correct data.
