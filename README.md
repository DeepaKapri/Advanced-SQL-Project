# Advanced-SQL-Project
This project is focused on analyzing sales data using advanced SQL techniques. The main goal was to clean, explore, and optimize the dataset while using SQL queries to extract meaningful insights. I worked on various SQL operations such as data cleaning, aggregation, joins, subqueries, indexing, and performance optimization to enhance query efficiency and reporting.

Project Files:
sales_data.sql – A collection of SQL queries used for analysis.
Advanced SQL Project: Data Analysis Using SQL Features.pdf – A summary of findings and insights from the SQL queries.
README.md – Documentation of the project.

Steps:
️1. Data Import & Cleaning
Imported a sales dataset into MySQL.
Identified and removed duplicate records using SELECT DISTINCT and ROW_NUMBER().
Standardized text fields (e.g., customer names and product names) using UPPER(), LOWER(), and TRIM() functions.
Ensured data consistency by handling missing values and incorrect formats.
️2. Data Exploration & Aggregation
Identified the top 5 highest-selling products based on total sales using SUM(quantity_ordered).
Found the top 3 customers who spent the most using SUM(total_sales).
3️. SQL Joins & Relationships
Used INNER JOIN to connect customer data with their order history, showing details like order date and total amount spent.
Used LEFT JOIN to list all customers, including those who haven’t placed any orders yet, ensuring a complete customer overview.
4️. Subqueries & Common Table Expressions (CTEs)
Used a subquery to find the customer who made the highest purchase.
Created a CTE (WITH statement) to filter high-value orders (above $500), making it easier to analyze premium customers.
5️. Query Optimization & Performance Improvement
Added indexes to frequently queried columns (e.g., customer_id and product_id) to speed up searches.
Used EXPLAIN ANALYZE to check query execution plans and identify ways to optimize performance.
6️. Export & Visualization
Exported query results to CSV format for further analysis.
Suggested ways to visualize key findings in Power BI or Excel, including charts for sales trends, top customers, and best-selling products.

Key Insights & Findings:
The top-selling product contributed to a significant percentage of total sales, showing the importance of promoting high-demand items.
A small group of customers accounted for a large portion of revenue, highlighting the value of customer retention.
Some customers had no purchase history, which presents an opportunity for targeted marketing efforts.
Performance optimization significantly improved query execution times, making data retrieval more efficient.

What I Learned:
Data cleaning is crucial – even a well-structured dataset can have inconsistencies that affect analysis.
Joins and subqueries help extract deep insights from relational databases.
Indexes and query optimization techniques can drastically improve performance.
Data visualization bridges the gap between raw data and actionable insights.
Exporting Data for Visualization
