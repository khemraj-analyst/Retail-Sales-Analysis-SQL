# Retail Sales Analysis using SQL

## Project Overview
This project analyzes retail sales data using PostgreSQL to explore sales performance, monthly and yearly trends, and customer purchasing behavior.

## Tools Used
- PostgreSQL
- pgAdmin

## Dataset
The dataset contains retail transaction details, including transaction ID, sale date and time, customer ID, gender, age, product category, quantity, price per unit, cost of goods sold (COGS), and total sale.

## SQL Skills Demonstrated
- Data exploration and data-quality checks
- Filtering and sorting with `WHERE` and `ORDER BY`
- Aggregations with `COUNT`, `SUM`, `AVG`, `MIN`, and `MAX`
- `GROUP BY` and `HAVING`
- Date and time analysis
- Common Table Expressions (CTEs)
- Window functions, including `LAG` and `ROW_NUMBER`
- `CASE` statements
- Month-over-Month (MoM) sales growth

## Business Questions
1. Retrieve all columns for sales made on `2022-11-05`.
2. Retrieve all transactions where the category is `Clothing`, the quantity sold is greater than 10, and the sale occurred in November 2022.
3. Calculate total sales for each category.
4. Find the average age of customers who purchased items from the `Beauty` category.
5. Find all transactions where `total_sale` is greater than 1000.
6. Find the total number of transactions made by each gender in each category.
7. Calculate the average sale for each month and find the best-selling month in each year.
8. Find the top 5 customers based on the highest total sales.
9. Find the number of unique customers who purchased items from each category.
10. Calculate the number of orders in each shift: Morning, Afternoon, and Evening.

## Project Findings
- Analyzed 1,997 retail transactions using PostgreSQL.
- Identified 155 unique customers in the dataset.
- Total sales revenue was 911,720.00.
- The average sale per transaction was 456.54.
- Analyzed monthly and yearly sales trends.
- Compared sales performance across product categories.
- Identified the top 5 customers by total sales.
- Analyzed customer purchasing behavior by gender and age.
- Examined transaction counts across morning, afternoon, and evening shifts.

## Author
Khemraj

Aspiring Data Analyst | PostgreSQL | SQL
