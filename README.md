# sql-data-analytics-project
📊 SQL Data Analytics Analytics Project (MySQL + EDA + ADA)
🧭 Project Overview

This project builds upon a MySQL-based Data Warehouse implementation guided by Data with Baraa.
The repository (data-warehouse-project) contains all ETL, transformation, and analytics scripts.

The objective is to convert raw transactional data into meaningful business insights using structured Exploratory Data Analysis (EDA) and Advanced Data Analytics (ADA) techniques.
All the scripts are created 

The analysis focuses on analyzing a structured Gold Layer and deriving actionable insights for customers, products, and sales performance.

📁 Project Structure
📦 sql-data-analytics
├── 📄 EDA.sql   → Exploratory Data Analysis queries
├── 📄 ADA.sql   → Advanced Data Analytics queries
├── 📄 README.md → Project documentation

🔍 EDA – Exploratory Data Analysis

The EDA phase focuses on understanding the dataset structure and identifying key patterns.
  Key analyses performed:
  Data quality checks (NULLs, duplicates)
  Customer distribution analysis
  Product category breakdown
  Sales trends overview
  Order frequency and behavior patterns
  Revenue distribution across categories

Objective:
To understand what the data looks like before applying business logic.


📈 ADA – Advanced Data Analytics

The ADA phase transforms raw data into business-ready insights.
Key analyses performed:

👤 Customer Analytics
Customer segmentation (VIP / Regular / New)
Lifetime value analysis
Purchase frequency
Average monthly revenue per customer

📦 Product Analytics
Revenue contribution by category & subcategory
High / Medium / Low performing products
Product lifecycle analysis
Average selling price and demand patterns

💰 Sales Analytics
Total revenue trends
Order-level performance
Customer contribution to revenue (Pareto analysis)

🧠 Key Insights
Revenue is highly concentrated in a few product categories (Pareto effect).
A small percentage of customers contribute majority of revenue.
Certain products show high revenue but low customer diversity.
Customer lifecycle significantly impacts revenue contribution.

🛠️ Tech Stack
MySQL (Data Warehousing & Analysis)
SQL (CTEs, Joins, Window Functions, Aggregations)
Data Modeling (Star Schema – Gold Layer)
Analytical Thinking (EDA + ADA)

🎯 Learning Outcome
This project helped in:
Building real-world data warehouse logic
Understanding analytical SQL patterns
Performing structured business analysis
Translating raw data into actionable insights
