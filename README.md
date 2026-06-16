# 🛍️ Customer Loyalty Analytics Project

## 📌 Overview
This project is an end-to-end Customer Loyalty Analytics solution designed to analyze customer shopping behavior and extract meaningful business insights related to revenue, customer segmentation, product performance, and purchasing patterns.

The project follows a complete data pipeline:

**Python (Data Cleaning & Feature Engineering) → SQL Server (Analysis Layer) → Power BI (Visualization Dashboard)**

---

## 🎯 Business Problem
Retail businesses need to understand:
- Who are the most valuable (loyal) customers?
- Which customers generate the highest revenue?
- What factors influence customer spending behavior?
- How do discounts and subscriptions impact sales performance?

This project answers these questions using real-world data analytics techniques.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy) → Data cleaning & feature engineering
- SQL Server (T-SQL) → Data analysis & stored procedures
- Power BI → Interactive dashboard visualization

---

## 📁 Project Structure

dashboard/
│   Customer_Behavior_Dashboard.pbix

data_extraction_cleaning/
│   main.py

dataset/
│   customer_shopping_behavior.csv

sql/
│   sp_customer_loyalty_analysis.sql

README.md

---

## ⚙️ Workflow

### 1. Data Cleaning (Python)
- Loaded dataset using Pandas
- Handled missing values
- Standardized column names
- Created new features:
  - Age grouping
  - Purchase frequency mapping
- Prepared dataset for SQL analysis

---

### 2. SQL Analysis Layer
- Stored cleaned dataset in SQL Server
- Created stored procedure for automated analysis
- Performed business queries such as:
  - Revenue by gender
  - Subscription impact on spending
  - Customer segmentation (Loyal / Returning / New)
  - Product performance analysis
  - Discount usage behavior

---

### 3. Power BI Dashboard
The dashboard provides interactive insights including:
- KPI Cards (Revenue, Customers, Average Spend)
- Customer segmentation analysis
- Revenue breakdown by category
- Product performance insights
- Interactive slicers for filtering data

---

## 📊 Key Business Insights
- Loyal customers contribute a significant portion of total revenue
- Subscription status influences average customer spending
- Certain product categories dominate overall sales performance
- Discount usage varies significantly across product types
- Customer segmentation helps identify high-value customers

---

## 🚀 How to Run This Project

### 1. Clone Repository
git clone https://github.com/your-username/customer-loyalty-analytics.git

---

### 2. Install Dependencies
pip install pandas numpy sqlalchemy pyodbc

---

### 3. Run Python Script
python data_extraction_cleaning/main.py

---

### 4. SQL Server Setup
- Create database: customer_behavior
- Run stored procedure:
sql/sp_customer_loyalty_analysis.sql

---

### 5. Power BI Dashboard
- Open:
dashboard/Customer_Behavior_Dashboard.pbix
- Connect to SQL Server database

---

## 🧠 What This Project Demonstrates
- End-to-end data analytics pipeline
- Data cleaning and transformation using Python
- Advanced SQL analysis and stored procedures
- Business intelligence reporting with Power BI
- Real-world customer behavior analysis

---

## 👨‍💻 Author
Youssif Mossad  
Aspiring Data Engineer 
MSA University  

---

## ⭐ Support
If you find this project useful, consider giving it a ⭐ on GitHub
