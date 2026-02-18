# Elevate_task3
shopping trends
# E-commerce SQL Data Analysis

## Project Overview
This project analyzes an online retail dataset containing transaction data from 2010-2011. The analysis covers customer behavior, product performance, and sales trends using SQL.

## Tools Used
- MySQL 8.0
- MySQL Workbench
- Dataset: UCI Online Retail Dataset (541,909 rows)

## Key Analyses
1. **Customer Analysis**: RFM segmentation, lifetime value, cohort analysis
2. **Product Analysis**: Best sellers, price points, bundling
3. **Sales Analysis**: Monthly trends, country performance
4. **Advanced SQL**: Subqueries, CTEs, window functions, views

## Files Description
- `01_basic_queries.sql`: SELECT, WHERE, GROUP BY, ORDER BY
- `02_aggregates.sql`: SUM, AVG, COUNT, MIN, MAX
- `03_joins.sql`: INNER, LEFT, RIGHT JOIN examples
- `04_subqueries.sql`: Correlated and nested subqueries
- `05_views.sql`: Customer, product, and sales views
- `06_optimization.sql`: Indexes and query optimization
- `07_interview_answers.sql`: SQL interview questions
- `08_complete_analysis.sql`: Advanced analytics

## Key Findings
- Total Revenue: £X,XXX,XXX
- Average Order Value: £XXX.XX
- Top Country: United Kingdom (XX% of sales)
- Best-selling Product: XXXX

## Interview Questions Answered
1. **WHERE vs HAVING**: WHERE filters rows before grouping, HAVING filters after
2. **JOIN Types**: INNER, LEFT, RIGHT, FULL OUTER, CROSS
3. **Average Revenue Per User**: `SELECT AVG(customer_total) FROM (SELECT SUM(amount) FROM orders GROUP BY customer)`
4. **Subqueries**: Queries nested inside other queries
5. **Optimization**: Indexes, EXPLAIN, avoiding SELECT *, appropriate JOINs
6. **Views**: Virtual tables for simplified complex queries
7. **NULL Handling**: COALESCE, IS NULL, IFNULL functions

## Screenshots
[Include screenshots of key query results]
