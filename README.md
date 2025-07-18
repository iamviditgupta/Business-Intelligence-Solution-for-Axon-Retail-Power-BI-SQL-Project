# Business-Intelligence-Solution-for-Axon-Retail-Power-BI-SQL-Project
End-to-end BI implementation using Power BI and SQL for Axon, a classic car retailer, to transform raw MySQL sales data into interactive dashboards and data-driven insights for improved decision-making.

The Axon Retail BI project is a full-scale business intelligence solution designed to help a classic car retailer unlock the power of its sales and customer data. Built using Power BI connected to a MySQL database, this project transforms raw, multi-table transactional data into a suite of dynamic, decision-ready dashboards.

At its core, the project addresses Axon's need to track sales trends, monitor office performance, understand customer behavior, and identify top-performing products—all in one centralized and visually engaging platform. The data model follows a snowflake schema, with linked tables capturing product lines, customers, payments, employees, and regional offices. Using Power Query, extensive data cleaning was performed—nulls were handled, formats were standardized, and complex date columns were parsed for granular time-based analysis.

The heart of the solution lies in three custom-built dashboards:

The Home Dashboard provides an at-a-glance view of global performance: total orders, revenue, profit margins, and office-wise comparisons. Interactive filters allow users to drill down by year, region, or product category.

The Product & Order Dashboard dives deeper into inventory dynamics. Users can identify the most in-demand products, visualize monthly sales spikes, and compare order volumes across time.

The Customer Insights Dashboard highlights the financial and geographic distribution of Axon's customer base. It surfaces the top 10 paying clients, average credit limits, and region-wise revenue breakdowns—empowering marketing and finance teams alike.

What makes the experience even more powerful is the seamless integration of SQL-backed KPIs and queries. Complex logic, such as identifying the top 5 products by sales quantity or the highest-paying customers, was written and validated in MySQL and imported into Power BI as refined datasets. This ensures both analytical accuracy and performance efficiency.

As for the insights? They’re game-changing. Offices in the USA and France outperformed others in profit margins. Customers in Spain and the US contributed the most to payments. Certain product lines dominated the revenue charts, while others showed seasonal patterns worth leveraging. The data even revealed a clear growth trajectory in Axon’s performance post-2003—hinting at successful expansion strategies.

More than just visuals, this BI system gives Axon’s decision-makers a tool to act faster, think smarter, and see clearer. Whether it’s the CFO planning next quarter’s strategy or a regional manager reviewing sales trends, every view tells a story—and every chart empowers action.
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
