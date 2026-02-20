# TASK-6-DATA-ANALYST
Data Analyst Internship Task
Purpose of the Task

The purpose of this task was to perform a sales trend analysis by calculating monthly revenue and order volume using SQL aggregation techniques. The aim was to understand how to summarize transactional data into meaningful business insights.

Dataset Overview

The analysis was performed on the online_sales table, which contains transactional sales data with the following attributes:

order_id – Unique identifier for each transaction

order_date – Date when the order was placed

amount – Revenue generated from the order

product_id – Identifier of the product sold

This dataset represents raw sales records that require grouping and aggregation for trend analysis.

🛠 Methodology

The task was completed using structured query language (SQL) in MySQL Workbench.

The following steps were performed:

The data was grouped by year and month using date extraction functions.

Monthly revenue was calculated using the SUM() aggregate function.

Monthly order volume was determined using COUNT(DISTINCT order_id) to ensure unique orders were counted.

The GROUP BY clause was applied to organize the data into monthly segments.

The ORDER BY clause was used to sort results chronologically.

The top three months with the highest sales were identified using sorting and limiting techniques.

Key Insights Generated

Monthly revenue trends were identified.

Order volume growth was analyzed over time.

Peak sales months were determined.

Time-based grouping helped in understanding seasonality and sales patterns.

Skills Demonstrated

Data aggregation

Time-series grouping

SQL query structuring

Business data interpretation

Analytical thinking

Learning Outcome

Through this task, I gained practical experience in transforming raw sales data into summarized monthly reports. This exercise strengthened my understanding of SQL aggregation functions and their importance in business performance analysis.

Summary

This task demonstrates how SQL can be used to analyze time-based trends in sales data. By applying aggregation and grouping techniques, meaningful performance metrics such as revenue and order volume can be generated to support business decision-making.
