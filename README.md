📊 Customer Behavior Analysis

This project focuses on analyzing customer purchasing behavior to understand spending patterns, discount usage, subscription trends, and product performance. The analysis follows an end-to-end analytics workflow, starting from data cleaning in Python, querying insights using SQL, and visualizing key metrics through an interactive Power BI dashboard.

The objective is to convert raw customer data into actionable business insights that support marketing, pricing, and customer engagement strategies.

🧰 Tools & Technologies

Python – Data cleaning, preprocessing, and feature engineering
SQL (PostgreSQL) – Business-driven analysis and querying
Power BI – Dashboard design and data visualization

📂 Dataset Details

Total records: ~4,000 rows
Total features: 18 columns
Data type: Customer transactions and behavioral attributes
Currency: USD
Key attributes include:
Customer demographics (age group, gender)
Purchase amount and discount usage
Subscription status
Product categories and review ratings
Previous purchase history

🔄 Data Processing Workflow
1️⃣ Data Cleaning & Transformation (Python)

Handled missing values using statistical imputation techniques
Standardized data types and transformed columns
Performed feature enineering to support behavioral analysis
Validated data quality by checking duplicates and distributions

2️⃣ Data Analysis (SQL)

The cleaned dataset was loaded into PostgreSQL to answer 10 business-driven questions, including:
Revenue contribution by gender and age group
High-spending customers who used discounts
Product categories with the highest average review ratings
Spending comparison between subscribed and non-subscribed customers
Customer segmentation into New, Returning, and Loyal groups
Top-selling products and discount-driven purchases
Advanced SQL concepts such as CTEs, aggregations, conditional logic, and ranking were applied to derive insights.

3️⃣ Visualization (Power BI)
An interactive dashboard was built to highlight key customer behavior metrics and trends.

Key KPIs:
Average Review Rating: 3.75
Average Purchase Amount: $59.76
Revenue distribution by customer segments
Product category performance

🔍 Key Business Insights

Male customers contribute higher overall revenue compared to female customers.
Non-subscribed customers generate more total revenue than subscribed users.
Accessories such as jewelry, sunglasses, and belts show strong sales volume.
Young adults contribute the highest revenue among age groups ($62,143).
Clothing is the most frequently purchased category.
A significant number of customers spend above the average purchase value despite using discounts.

🎯 Business Value

This analysis helps businesses:

Understand customer spending behavior across demographics
Identify profitable product categories and customer segments
Evaluate the impact of discounts and subscriptions on revenue
