# Online Bookstore SQL Data Analysis

## Project Overview
This project focuses on analyzing an online bookstore database using PostgreSQL. It explores books, customers, and orders to answer business-related questions about sales, revenue, customer purchasing behavior, and inventory.

## Tools Used
- PostgreSQL
- SQL

## Database Structure
The database contains three tables:

- **Books:** Book title, author, genre, publication year, price, and stock.
- **Customers:** Customer name, email, phone, city, and country.
- **Orders:** Customer orders, book IDs, order dates, quantities, and total amounts.

## SQL Skills Demonstrated
- Database and table creation
- Primary and foreign keys
- Filtering and sorting using WHERE and ORDER BY
- Aggregate functions: SUM, AVG, COUNT
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- DISTINCT, LIMIT, and BETWEEN
- COALESCE for handling NULL values

## Business Questions Answered
- Which books belong to the Fiction genre?
- Which books were published after 1950?
- What is the total stock and revenue recorded?
- Which book has the highest price?
- How many books were sold in each genre?
- Which customers have placed at least two orders?
- Which book is ordered most frequently?
- Which authors have sold the most books by quantity?
- Which customer has spent the most?
- What is the estimated remaining stock after accounting for recorded order quantities?

## Project File
- `SQL onlinebookstore.sql` — SQL script containing database setup and analysis queries.

## Key Findings
The SQL script contains queries designed to explore sales, customer behavior, book pricing, and inventory. Actual numerical findings can be added after executing the queries and reviewing their results.

## How to Run
1. Create or connect to a PostgreSQL database.
2. Import the Books, Customers, and Orders CSV files.
3. Execute the SQL script in a PostgreSQL-compatible environment.
4. Review the query results.

**Note:** Update the CSV import paths to match your local environment before running the script.

## Author
Mohammd-Insaf
