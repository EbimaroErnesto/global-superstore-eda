Global Superstore Sales — Exploratory Data Analysis (EDA)
 Project Overview

This project performs an exploratory data analysis (EDA) on a global retail sales dataset to uncover patterns in sales performance, profitability, discount strategies, shipping efficiency, and product-level performance.
The goal is to derive actionable business insights that can support pricing, logistics, and operational decision-making.

 Objectives

Understand overall sales and profit distribution

Analyze the impact of discounts on profitability

Examine how shipping speed and cost affect profit

Identify high-revenue but loss-making products

Translate data findings into business-relevant insights

Dataset Description

The dataset contains 51,290 transactions with 27+ features, including:

Order and shipping dates

Customer and market information

Product categories and sub-categories

Sales, profit, discount, and shipping cost metrics

Each row represents a single order placed across global markets.

Tools & Technologies

Python

Pandas — data manipulation

Matplotlib & Seaborn — data visualization

Jupyter Notebook — interactive analysis

Git & GitHub — version control

Data Preparation & Feature Engineering

Key preprocessing steps included:

Converting order and ship dates to datetime format

Creating new features such as:

Delivery_Days

Order_Year

Order_Month

Removing redundant or non-informative columns

Verifying data quality (no missing values)

 
Key Analyses & Insights

1. Sales Distribution

Sales values are highly right-skewed

Most transactions are low-value, while a few large orders dominate revenue

2. Impact of Discounts on Profitability

Orders with discounts up to 20% remain profitable on average

Discounts above 20% consistently lead to losses

Discounts above 40% are both frequent and highly loss-making

Insight: Aggressive discounting erodes profit margins and poses significant financial risk.

3. Shipping Speed, Cost, and Profitability

Same-day and next-day deliveries incur the highest shipping costs

Moderate delivery times (4–6 days) achieve the best balance between cost and profit

Faster delivery does not guarantee higher profitability

Insight: Optimizing delivery speed is more effective than maximizing speed.

4. High-Sales but Loss-Making Products

Several products generate high total sales but negative total profit

Loss-making items are often bulky products (e.g., furniture, large electronics)

Losses are likely driven by high shipping costs and deep discounts

Insight: Revenue alone is not a reliable indicator of product success.

Key Business Takeaways

Profitability is highly sensitive to discount policy

Shipping cost is a major hidden driver of losses

Certain products require repricing, discount caps, or logistics optimization

Data-driven policy changes can significantly improve margins


 Next Steps

Build a regression model to predict profit or sales

Perform customer segmentation using clustering

Extend analysis to time-series forecasting


 Author

Ernest Ebimaro
Data Science & Analytics Enthusiast
