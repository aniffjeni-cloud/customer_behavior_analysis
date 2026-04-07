# customer_behavior_analysis
This project explores customer purchasing patterns using a dataset of 3,900 transactions across multiple product categories. The objective is to derive actionable business insights related to customer behavior, spending trends, and product performance. This project is showcasing customer behavior analysis using python, SQL, and Power Bi. 

The goal is to uncover insights into:

Customer spending patterns
Product preferences
Subscription behavior
Business performance drivers

These insights can help businesses make data-driven decisions to improve revenue and customer retention.

📂 Dataset Summary
Feature	Description
Rows	3,900
Columns	18
Data Includes	Demographics, purchase details, and shopping behavior
Key Columns:
Customer: Age, Gender, Location, Subscription Status
Purchases: Item, Category, Amount, Season
Behavior: Discounts, Promo Code, Frequency, Ratings, Shipping Type

⚠️ Missing Data:

37 missing values in Review Rating column (handled during preprocessing)
🛠️ Tech Stack
Python (Pandas) → Data Cleaning & Feature Engineering
PostgreSQL → Data Analysis using SQL
Power BI → Dashboard & Visualization

🧹 Data Cleaning & Preparation
Loaded dataset using Pandas
Handled missing values using median imputation (category-wise)
Standardized column names to snake_case
Created new features:
age_group
purchase_frequency_days
Removed redundant columns (promo_code_used)
Exported cleaned data to PostgreSQL

📊 Key Business Analysis (SQL)
🔹 Revenue Insights
Revenue comparison by Gender
Revenue contribution by Age Group
🔹 Customer Behavior
Identified high-spending discount users
Analyzed repeat buyers vs subscription behavior
Segmented customers into:
New
Returning
Loyal
🔹 Product Analysis
Top 5 products by review rating
Top 3 products per category
Identified discount-dependent products
🔹 Operational Insights
Compared Standard vs Express shipping
Analyzed Subscribers vs Non-subscribers

📈 Dashboard (Power BI)

📌 Interactive dashboard created to visualize:

Revenue trends
Customer segmentation
Product performance
Purchase behavior

Business Recommendations
🎯 Promote subscription plans with exclusive benefits
🎁 Implement loyalty programs for repeat customers
💸 Optimize discount strategies to maintain profit margins
🛍️ Highlight top-performing products in marketing campaigns
📢 Use targeted marketing for high-value customer segments

Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_cleaning_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md

🚀 Key Learnings
End-to-end data analysis workflow
Data cleaning & feature engineering using Pandas
Writing real-world SQL queries for business problems
Building interactive dashboards in Power BI
Translating data insights into business recommendations


⭐ If you like this project

Give it a ⭐ on GitHub and feel free to connect!
