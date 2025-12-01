Credit Card End-to-End Analytics Project

This project provides a complete analytics workflow using Excel, PostgreSQL, SQL, Power Query, DAX, and Power BI. It covers the entire process from raw CSV files to interactive dashboards that reveal key insights into credit card transactions, customer demographics, revenue patterns, and spending behavior.

Project Workflow

Started with two CSV files in Excel (10,000+ rows each).

Created a PostgreSQL database and built two tables:

cc_detail for transaction data

cust_detail for customer data

Loaded both datasets into PostgreSQL.

Connected the database to Power BI and created a data pipeline.

Performed data cleaning and transformation in Power Query.

Added calculated columns and measures using DAX.

Designed two Power BI dashboards: Transaction Insights and Customer Insights.

Key Insights
Transaction Dashboard

Total Revenue: 55M

Total Interest: 8M

Total Transaction Amount: 45M

Total Transaction Count: 656K

Blue card generated the highest revenue at 46M.

Q3 recorded the highest revenue (14.2M) and transaction count (166.6K).

Bills, Entertainment, and Fuel were the top spending categories.

Businessmen generated the highest revenue at 17.4M.

Swipe method contributed the most revenue (35M).

Customer Dashboard

Total Revenue: 55M

Total Income: 576M

Male customers generated 30M; female customers generated 25M.

Age group 40–50 contributed the highest: 24M.

States TX, NY, and CA were the top contributors.

High salary group generated 29M in revenue.

Married customers generated 28M.

Graduates contributed 22M.

Tools Used

Excel – Raw data (CSV)

PostgreSQL – Database creation and SQL queries

Power BI – Dashboarding and DAX

Power Query – Data cleaning and transformation

SQL / DAX – Data modeling and calculations

How to Use

Import SQL scripts into PostgreSQL to create the tables.

Load both CSV files into the respective tables.

Open the Power BI files and connect them to PostgreSQL.

Apply Power Query steps and refresh the model.

View or customize the dashboards.
