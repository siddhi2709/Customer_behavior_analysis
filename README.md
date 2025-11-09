# Customer_behavior_analysis
Project Overview 
This project analyzes customer shopping behavior. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

Dataset Summary 
Rows - 3900
Columns - 18
Key Features - Age, Gender, Location, Subscription Status, Item Purchased, Category, Purchase Amount, Season, Size, Color, Discount Applied, Promo Code Used, Review Rating, Shipping Type, Frequency of Purchases.

Data Preparation & EDA 
1. Data Loading: Imported dataset using pandas.
2. Initial Exploration: Used df.info() and df.describe() for structure and summary.
3. Missing Data Handling: Imputed missing review_rating values with median per product category.
4. Column Standardization: Renamed columns to snake_case for readability.
5. Feature Engineering: Created purchase_frequency_days to capture buying habits.
6. Data Consistency Check: Removed redundant promo_code_used column.
7. Database Integration: Loaded cleaned dataset into Mysql Server for structured SQL analysis.

Power BI Dashboard 
An interactive dashboard was developed in Power BI to visualize insights including:
- Sales by category and gender
- Subscription vs. non-subscription performance
- Revenue trends by age group
- Product rating distributions
- Shipping method comparisons
