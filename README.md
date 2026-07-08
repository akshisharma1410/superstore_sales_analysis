#  Superstore Sales Analytics
## End-to-End Data Analytics Project using Python, MySQL & Power BI

Note: The dashboard design uses a KIWI Superstore(Norway) inspired green color palette for visual aesthetics. The dataset used in this project is the publicly available Superstore Sales Dataset from Kaggle and is not affiliated with KIWI.

#  Project Overview

Businesses generate thousands of sales transactions every day, but raw data alone cannot answer important business questions. Decision-makers need insights into sales performance, customer behavior, product profitability, and operational efficiency to make informed decisions.

In this project, I analyzed the Superstore Sales Dataset containing 9,994 sales records and transformed raw transactional data into meaningful business insights.

The project follows a complete data analytics workflow from data cleaning and feature engineering in Python, business analysis in MySQL, and finally building an interactive Power BI dashboard to present insights in a clear and business-friendly format.


#  Business Problem

The objective of this project was to help business stakeholders answer questions such as:

- Which products and categories generate the highest revenue and profit?
- Which products consistently incur losses?
- Which customer segments contribute the most to sales?
- Who are the highest-value customers?
- Which customers reduce overall profitability?
- How does shipping performance impact business performance?
- Which states generate the highest profit?
- How has sales performance changed over time?

The goal is to support better business decisions using data-driven insights.


#  Tech Stack

-Python (Pandas & NumPy): Data Cleaning & Feature Engineering 
-SQLAlchemy: Export Clean Data to MySQL 
-MySQL: Business Analysis 
-Power BI: Dashboard & Data Visualization 
-GitHub: Project Portfolio 


#  Dataset Information

- Source: Kaggle Superstore Sales Dataset
- Rows: 9,994
- Columns: 21

The dataset contains information related to:

- Orders
- Customers
- Products
- Sales
- Profit
- Discounts
- Shipping
- Geographic Locations


#  Data Cleaning

The dataset was cleaned and prepared using Pandas before loading it into MySQL.

The cleaning process included:

- Creating a copy of the original dataset
- Checking for missing values and duplicate records
- Renaming columns to SQL-friendly names
- Converting date columns into datetime format
- Converting Postal Code to text format
- Standardizing column names and data types



#  Feature Engineering

  To support business analysis, the following additional features were created:

- Order Year
- Order Month
- Month Name
- Shipping Days
- Shipping Bucket
- Loss Flag
- Profit Margin (%)

These features helped analyze sales trends, shipping efficiency, and profitability more effectively.


#  SQL Business Analysis

  The cleaned dataset was exported to MySQL using SQLAlchemy.

  Business questions were answered using SQL, including:

- Overall Revenue & Profit
- Revenue and Profit by Category
- Top Revenue-Generating Products
- Most Profitable Products
- Loss-Making Products
- Customer Segment Performance
- Top Customers by Revenue
- Monthly Revenue Trend
- Year-over-Year Revenue Growth
- Shipping Performance
- State-wise Profitability
- Loss-Making Customers

The SQL analysis demonstrates the use of:

- Common Table Expressions (CTEs)
- Window Functions
- Ranking Functions
- Aggregate Functions
- Subqueries


#  Dashboard

An interactive two-page Power BI dashboard was developed to communicate business insights.

##  Page 1 – Sales Performance Overview

This page provides a high-level overview of overall business performance.

Highlights:

- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Total Customers
- Revenue & Profit by Category
- Top Revenue-Generating Sub-Categories
- Yearly Revenue Trend
- Top Revenue-Generating Products



## Page 2 – Customer & Operational Insights

This page focuses on customer behavior and operational performance.

Highlights:

- Customer Segment Performance
- Shipping Bucket Performance
- Revenue, Profit & Profit Margin by State
- Top Customers by Revenue
- Loss-Making Customers

Interactive slicers allow users to filter the dashboard by:

- Order Year
- Category
- Segment
- Region


#  Key Insights

- The Consumer segment generated the highest revenue and profit.
- A small number of products contributed a significant share of total revenue.
- Standard Shipping accounted for the majority of sales.
- Profitability was concentrated in a few high-performing states.
- A small number of customers consistently generated losses, indicating opportunities to review pricing and discount strategies.


#  Business Recommendations

Based on the analysis, the following recommendations could help improve business performance:

- Increase focus on high-performing products and categories through better inventory planning and targeted marketing.
- Review loss-making products to identify pricing, procurement, or discount-related issues.
- Strengthen relationships with high-value customers while reviewing customers that consistently generate losses.
- Apply successful sales strategies from high-performing states to improve performance in lower-performing regions.
- Continue monitoring shipping performance to improve operational efficiency and customer satisfaction.


#  Project Workflow

-Raw Kaggle Dataset
-Python (Pandas)
 Data Cleaning & Feature Engineering
-SQLAlchemy
 Export Clean Data to MySQL
-MySQL
 Business Analysis
-Power BI
 Interactive Dashboard & Business Insights


#  Repository Structure

superstore-sales-analytics/
│
├── python_analysis.ipynb
├── sql_analysis.sql
├── powerbi_dashboard.pbix
├── dashboard_images/
├── dataset/
└── README.md


#  About This Project

This project was developed as part of my data analytics portfolio to demonstrate practical skills in Python, SQL, and Power BI by solving business problems using transactional sales data.

It showcases the complete analytics workflow—from preparing raw data and writing SQL queries to designing an interactive dashboard that communicates insights in a business-friendly manner.
