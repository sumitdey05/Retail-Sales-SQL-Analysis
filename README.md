🛍️ Retail Sales Analysis: End-to-End SQL Exploration
By: Sumit Dey | Data Analyst Project

📌 Project Overview
This project serves as a comprehensive introduction to the data analysis workflow, focusing on exploratory data analysis (EDA) and business intelligence using SQL. I acted as a Data Analyst for a retail corporation, transforming a raw dataset of 2,000+ transactions into a structured database to uncover trends in customer demographics, peak sales periods, and category performance.

🚀 Strategic Objectives
Data Integrity & ETL 🧹: Orchestrated the extraction and cleaning of raw CSV data, implementing rigorous NULL value checks and schema validation.

Exploratory Data Analysis (EDA) 🔍: Conducted deep-dive exploration to determine dataset volume, customer diversity, and product segmentation.

Business Intelligence (BI) 💡: Engineered complex SQL queries to solve 10 specific business challenges, providing data-driven answers to operational questions.

📊 Dataset Architecture
The dataset encompasses a granular view of retail operations:

Temporal Data: Transaction ID, Date, and precise Time of sale.

Customer Demographics: Unique IDs, Gender, and Age tracking.

Product Segmentation: Categorization across Beauty, Clothing, and Electronics.

Financial Metrics: Quantity sold, Price per Unit, Cost of Goods Sold (COGS), and Total Revenue (Total Sale).

🛠️ Technical Workflow
1. Database Engineering & Data Scrubbing 🧼
I initiated the project by building a robust environment to ensure "Clean Data" for analysis:
Schema Design: Defined the retail_sales_analysis table with optimized data types for high performance
Quality Assurance: Developed multi-column NULL check queries to identify data gaps.
Record Sanitization: Executed DELETE operations on incomplete records to prevent mathematical skewing in financial reports.

2. Advanced Analytical Queries 🕵️‍♂️
I leveraged SQL to extract high-value insights, including:
Customer Lifecycle: Identified the top 5 high-value customers based on lifetime spend.
Operational Shifts: Categorized sales into Morning, Afternoon, and Evening shifts using CASE logic to optimize staffing recommendations.
Time-Series Trends: Utilized Window Functions to rank and identify the highest-performing month for each fiscal year.
Demographic Profiling: Analyzed average customer age within the 'Beauty' category to assist marketing targeting.


🧠 Technical Stack & Skills
Foundational SQL: CREATE, DROP, INSERT, DELETE
Data Aggregation: SUM(), AVG(), COUNT(), MAX(), MIN()
Advanced Logic: GROUP BY, ORDER BY, LIMIT, WHERE, BETWEEN
Analytical Functions: CASE Statements, Window Functions (RANK(), OVER, PARTITION BY), and Subqueries.

📈 Key Findings (Executive Summary)
Peak Traffic: Analysis revealed distinct peaks during specific time shifts (Morning vs. Evening), suggesting opportunities for time-based promotions.

Top Categories: Unique customer counts per category helped identify 'Clothing' and 'Electronics' as high-volume drivers.

High-Value Consumers: The top 5 customers significantly outperform the average transaction value, indicating a need for a loyalty program.

📂 Repository Structure
retail_sales_final.csv: The primary cleaned dataset.

SQL_Analysis_Script.sql: The full collection of scripts from table creation to final insights.

README.md: Project documentation.

🏁 Conclusion
This project demonstrates my proficiency in SQL and my ability to navigate the full data lifecycle—from messy raw data to polished business insights. It highlights my focus on data accuracy and logical problem-solving.

Let's Connect!
If you're looking for a detail-oriented Data Analyst or have feedback on this project, I’d love to hear from you.
📬 [linkedin: www.linkedin.com/in/sumit-dey-3686842a3]
