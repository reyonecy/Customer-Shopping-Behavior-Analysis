📊 Customer Shopping Behavior Analysis

End-to-End Exploratory Data Analysis & Business Intelligence Dashboard

📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional retail data to uncover meaningful insights into spending patterns, customer segments, product preferences, and subscription behavior.

The analysis combines Python-based Exploratory Data Analysis (EDA), SQL-driven business queries, and an interactive Power BI dashboard to support data-driven decision-making.

🎯 Objectives

Understand customer purchasing behavior across demographics

Identify high-value customers and product trends

Analyze the impact of discounts and subscriptions on revenue

Build an interactive dashboard for business stakeholders

Provide actionable business recommendations

🗂 Dataset Summary

Total Records: 3,900 customer transactions

Total Features: 18 columns

Key Attributes:

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Behavioral Metrics:

Discount Applied

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

Data Quality:

Missing values detected in Review Rating (37 entries), handled during preprocessing.

🧪 Exploratory Data Analysis (Python)

EDA was performed using Python (Pandas, NumPy, Matplotlib/Seaborn) with a structured approach:

🔹 Data Preparation & Cleaning

Loaded dataset and inspected schema using .info() and .describe()

Handled missing values in Review Rating using median imputation by product category

Standardized column names to snake_case

Removed redundant features (promo_code_used) after consistency checks

🔹 Feature Engineering

Created age_group bins to analyze demographic trends

Derived purchase frequency indicators

Prepared clean, analysis-ready data for downstream use

🔹 Database Integration

Connected Python pipeline to PostgreSQL

Stored cleaned dataset for advanced SQL-based analysis

🛢 Data Analysis Using SQL (PostgreSQL)

Business-oriented queries were written to answer key questions:

Revenue comparison by Gender

Identification of high-spending discount users

Top 5 products by average rating

Purchase amount comparison by Shipping Type

Spending behavior of Subscribers vs Non-Subscribers

Products most dependent on discounts

Customer segmentation into New, Returning, and Loyal

Top 3 products within each category

Relationship between repeat purchases and subscriptions

Revenue contribution by Age Group

📈 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize insights effectively.

🔹 Key KPIs & Filters:

Filters:

Gender

Subscription Status

Shipping Type

Product Category

KPIs Displayed:

Total Revenue

Average Purchase Amount

Customer Segmentation

Subscription Impact

Category-wise Performance

The dashboard enables dynamic exploration of customer behavior and supports quick executive-level insights.

💡 Business Recommendations

Based on the analysis, the following recommendations were derived:

Increase Subscription Adoption
Offer exclusive benefits and targeted promotions for subscribers.

Strengthen Customer Loyalty Programs
Incentivize repeat buyers to transition into loyal customers.

Optimize Discount Strategy
Balance discount usage to maximize revenue without eroding margins.

Product Promotion Strategy
Highlight top-rated and best-selling products in marketing campaigns.

Targeted Marketing Campaigns
Focus efforts on high-revenue age groups and express-shipping users.

🛠 Tools & Technologies Used

Python: Pandas, NumPy, Matplotlib, Seaborn

SQL: PostgreSQL

BI Tool: Power BI

Environment: Jupyter Notebook
