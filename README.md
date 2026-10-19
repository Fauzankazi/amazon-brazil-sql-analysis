# amazon-brazil-sql-analysis
SQL-based e-commerce analytics using the Olist Brazilian E-Commerce Dataset


E-Commerce Performance Analysis
Project Overview

This project analyzes the Olist Brazilian E-Commerce Dataset through 14 SQL business questions. It explores revenue performance, customer purchasing behaviour, seller activity, payment methods, product reviews, delivery performance, and monthly demand trends.

The project uses an Amazon Brazil business scenario for analytical framing. The underlying data is from Olist, not Amazon's internal systems.
Business Questions

The analysis addresses:

Orders associated with sellers across states
Cumulative revenue by product category
Payment method usage and average order value
Highest-spending customer
Average review scores by category and destination state
Customer order frequency
Sellers and products with no associated orders
Top five categories by revenue
Median delivery time
Sellers performing above the platform average
Customers who ordered but never reviewed
Month with the highest order volume

Tools Used

MySQL 8+
SQL: JOINs, CTEs, aggregate functions, subqueries, window functions, date functions
Microsoft Excel for charts
Microsoft PowerPoint for presentation

Dataset
Olist Brazilian E-Commerce Dataset. The analysis combines relevant tables such as orders, order_items, customers, sellers, products, order_payments, and order_reviews.
File: https://drive.google.com/file/d/12Fb1OeUb_55_Fn_0rlOFHmoI5sieov7p/view?usp=sharing

Repository Contents

sql/ — SQL queries for the business questions
images/ — Selected charts and visualizations
E-Commerce-Performance-Analysis.pdf — Project presentation

Key Learnings

Translating business questions into SQL queries
Combining relational tables for analysis
Calculating revenue, order counts, averages, and median delivery time
Using window functions for cumulative analysis
Presenting findings with visualizations and business recommendations

Important Note
Results and recommendations are based on the Olist dataset and the definitions used in the queries. They should not be interpreted as actual Amazon business performance.

Author
Fauzan Sadik Kazi
