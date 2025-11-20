📊 Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer shopping patterns, spending behavior, and product preferences using Python, SQL, and Power BI. The goal of this project is to extract actionable insights that support data-driven business decisions.

🚀 Project Overview

This project analyzes 3,900+ retail transactions to understand how customers shop across different product categories. It focuses on discovering patterns in:

Customer demographics

Purchase behavior

Discount usage

Subscription patterns

Product ratings

Revenue contribution by segments

🗂️ Dataset Summary

Rows: 3,000

Columns: 18

Key Features:

Age, Gender, Location

Category, Item Purchased, Purchase Amount

Season, Size, Color

Discount Applied, Promo Code Used

Subscription Status

Review Rating, Shipping Type

Previous Purchases & Frequency

🛠️ Technologies Used

Python: Pandas, NumPy

SQL: MySQL

Power BI: Dashboards & Visualizations

Other: Data Cleaning, EDA, Feature Engineering

🧼 Data Cleaning & Preprocessing (Python)

✔ Loaded dataset using Pandas
✔ Handled missing values (median imputation for review ratings)
✔ Converted column names to snake_case
✔ Created new features:

age_group

purchase_frequency_days

✔ Verified redundancy between discount_applied and promo_code_used (removed promo_code)
✔ Exported cleaned data into MySQL database

📊 Data Analysis using SQL

Performed structured business analysis in MySQL:

Revenue by Gender

High-Spending Discount Users

Top 5 Products by Review Rating

Shipping Type Comparison (Standard vs Express)

Subscribers vs Non-Subscribers Revenue

Most Discount-Dependent Products

Customer Segmentation — New, Returning, Loyal

Top 3 Products per Category

Repeat Buyer Subscription Tendencies

Revenue by Age Group

📈 Power BI Dashboard

An interactive dashboard was created to visualize:

Revenue distribution

Customer segments

Purchase trends

Top-rated products

Season & category-based insights

Subscriber vs non-subscriber comparison

💡 Business Recommendations

Based on the findings:

Promote subscriber-only benefits to increase conversions

Launch customer loyalty programs for repeat buyers

Optimize discount strategies to protect profit margins

Highlight top-rated products in marketing campaigns

Target high-revenue age groups and express-shipping customers

🙌 Conclusion

This project demonstrates practical skills in data cleaning, SQL analytics, and business intelligence, and provides clear insights to help retail businesses improve customer experience and revenue.
