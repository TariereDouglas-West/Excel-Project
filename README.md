# Excel-Project
Dataset from Kaggle
orders sheet  – orders table

Columns A - E (Order Id, Order Date, Customer ID, Product ID, Quantity) was already populated in the dataset while columns F - M (Customer Name, Email, Country, Coffee Type, Roast Type, Size, Unit price, Sales) was not populated so data gathering was used to fill the data for these columns from other tables on other spreadsheets.

Data Gathering:

The customer data (Columns F-H) was gathered using XLOOKUP formula while the product data (columns I-M) was filled using Index match.

-	Empty cells were populated using IF.
-	Sales = Unit price * Quantity

New columns
-	Column N was introduced to show full coffee type name using ‘IF’ formula.
-	Column O was introduced to show full roast type name using ‘IF’ formula.

Formatting/Data Cleaning
-	Order Date (Column B) was previously 00-00-0000 (mm-dd-yy)
-	Size (Column K) was changed to decimal in kg.
-	Unit Price and Sales to Currency
-	Ensured no duplicates were found in dataset.

Changed the sheet to a table. 

Customer ID - foreign key

products sheet – products table

This is the products table with the Product ID as the primary key (PK 
