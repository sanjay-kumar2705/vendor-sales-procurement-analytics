Vendor Sales Procurement Analytics
📌 Project Overview

This project analyzes vendor performance, purchasing, sales, pricing, and profitability using SQL, Python, and Power BI.

The goal is to identify high-performing vendors, analyze purchasing and sales patterns, evaluate pricing, and generate meaningful business insights through data analysis and visualization.

-> Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SQL
SQLite
SQLAlchemy
Power BI
Git & GitHub
Jupyter Notebook
pbix

🔄 Project Workflow
Raw Data
   ↓
Data Ingestion
   ↓
SQLite Database
   ↓
SQL Analysis
   ↓
Python Data Cleaning & EDA
   ↓
Vendor Performance Analysis
   ↓
Power BI Dashboard

->SQL Analysis

SQL was used to:

- Combine data from multiple tables
- Analyze vendor purchasing patterns
- Calculate total purchase and sales values
- Analyze freight costs
- Identify top-performing vendors
- Compare purchase prices with actual selling prices
- Calculate vendor-level performance metrics

Common SQL concepts used:

- CTEs
- JOINs
- GROUP BY
- Aggregate functions
- CASE statements
- Subqueries

->Python Data Analysis

Python was used for data cleaning, transformation, exploratory data analysis, and visualization.

Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- sqlalchemy

Analysis Performed
- Data cleaning
- Missing-value analysis
- Duplicate detection
- Data type conversion
- Outlier analysis
- Vendor performance analysis
- Sales analysis
- Purchase analysis
- Price analysis
- Distribution analysis
- Correlation analysis
- Data visualization

->Power BI Dashboard

The cleaned and analyzed data was imported into Power BI to create an interactive dashboard.

- Dashboard Includes
- Total Sales
- Total Purchases
- Total Gross Profit
- Total Profit Margin
- Unsold Inventory
- Top Brands
- Top Vendors
- Purchase Contribution
- Low Performing Vendors

📈 Key Business Questions
- How much the Total Procurement is dependent on the top vendors?
- Does purchasing in bulk reduce the unit price, what is the optimal purchase volume for cost savings?
- Which vendor has low inventory turnover, indicating excess stock and slow-moving products?
- How much capital is locked in unsold inventory per vendor, and which vendors contribute the most to it?
- What is the 95% confidence intervals for profit margins of top-performing vendors?

💡 Key Insights

The analysis helps identify:

- High-performing vendors
- High-performing brands
- Purchasing patterns
- Sales opportunities
-Pricing differences
-Vendor profitability
