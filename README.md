# Using WHERE, Adding Conditions, ORDER BY, and Importing CSV Data

This project is a beginner-level SQL practice exercise focused on importing and querying data in MySQL. The dataset was originally stored in an Excel file named `my_practice_program_db`, which was exported as a CSV file and imported into MySQL using the **Table Data Import Wizard**. After importing the data, SQL queries were used to filter products based on multiple conditions and sort the results alphabetically by product name.

## Features

* Imports CSV data into MySQL using the Table Data Import Wizard.
* Retrieves imported data using `SELECT`.
* Filters records using the `WHERE` clause.
* Combines multiple conditions using `AND`.
* Filters products based on stock quantity and price.
* Sorts results using `ORDER BY`.

## SQL Query

```sql
SELECT *
FROM products
WHERE stock_quantity > 20 AND price < 80000
ORDER BY product_name;
```

## SQL Concepts Practiced

* `SELECT`
* `FROM`
* `WHERE`
* `AND`
* `ORDER BY`
* Filtering data
* Sorting data
* Importing CSV data into MySQL
* Using MySQL Table Data Import Wizard

## How to Run

1. Prepare the `my_practice_program_db` dataset in Excel.
2. Export the Excel data as a CSV file.
3. Open MySQL Workbench.
4. Use the **Table Data Import Wizard** to import the CSV file into MySQL.
5. Select or create the appropriate database and table.
6. Run the SQL query to retrieve products with more than 20 items in stock and a price below 80,000.
7. The results will be sorted alphabetically by `product_name`.

## Language

* SQL
* MySQL
