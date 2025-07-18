# Business-Intelligence-Solution-for-Axon-Retail-Power-BI-SQL-Project
End-to-end BI implementation using Power BI and SQL for Axon, a classic car retailer, to transform raw MySQL sales data into interactive dashboards and data-driven insights for improved decision-making.

📌 Project Title:
Business Intelligence Solution for Axon Retail (Capstone Project)

📊 Project Overview:
This project focuses on designing and implementing a Business Intelligence (BI) solution for Axon, a retailer dealing in classic cars. The company was facing challenges in analyzing its sales data effectively due to the lack of centralized reporting and real-time insights. The goal of this BI system was to provide Axon's management with interactive dashboards, real-time reports, and analytical tools that enhance decision-making.

💡 Objectives:
Integrate MySQL-based raw sales data into Power BI
Clean and transform the data using Power Query

Build intuitive dashboards for:
Product & order analysis
Customer & payment insights
Office-wise sales performance
Use SQL for advanced analytics, such as customer segmentation and sales ranking

🗂️ Tech Stack:
Power BI – Dashboarding & visual analytics
MySQL – Data source & analytical queries
Power Query Editor – Data cleaning and transformation
DAX – Measure creation and data modeling

🧱 Data Schema Overview:
Customers – Contact details, credit limits, locations
Products – SKUs, price, stock quantity
Orders & Order Details – Dates, quantities, revenue
Payments – Amount paid, dates, customer ID
Employees & Offices – Staff details and office locations
Schema followed: Snowflake schema due to table dependencies

🧼 Data Preparation Process:
Connected Power BI to MySQL database
Removed null columns, merged and cleaned categorical variables
Converted data types and dropped irrelevant columns
Ensured schema relationships for proper joins and slicing

📈 Dashboard Highlights:
Home Page:

Office-wise sales and profit summary
Net profit trend over time
Product & Order Analysis Page:
Top 5 products by quantity
Monthly sales trend by product
Order value and count distribution
Customer Analysis Page:
Top 10 paying customers
Average credit limit and payment trends
Country-wise customer segmentation
All pages include interactive slicers (by year, product line, and country).

🧮 SQL Analytics Performed:
Top 5 customers by credit limit
Top 5 orders by total revenue
Customers with highest order counts
Most ordered products by quantity
Top 10 customers by total payment amount
Monthly trend of sales and order volume

📊 Key Insights:
Q1 sales in 2003–2004 were low but improved steadily each year.
Offices in the USA and France showed consistently high profitability.
A significant increase in order counts and net profit margin over time.
Customers from USA and Spain made the highest payments overall.

✅ Recommendations:
Perform deeper seasonal analysis of product lines for better inventory planning.
Focus marketing efforts on top-paying customers in USA and Spain.
Prioritize scaling operations in high-performing offices like San Francisco and Paris.
Continue tracking quarterly sales to identify and act on emerging trends.
