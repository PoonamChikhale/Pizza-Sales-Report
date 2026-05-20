🍕 Pizza Sales Analytics Dashboard:
A dynamic and interactive Power BI dashboard developed to analyze pizza sales performance, customer ordering behavior, and product-level insights across multiple categories and sizes.
The dashboard transforms raw transactional sales data into meaningful business intelligence, helping stakeholders monitor revenue trends, identify top-performing products, and make data-driven operational decisions.


Purpose:
The Pizza Sales Analytics Dashboard is a visually engaging and analytical Power BI report designed to provide a comprehensive overview of sales performance for a pizza business.
The dashboard focuses on tracking revenue generation, order trends, product demand, and customer purchasing patterns to support strategic decision-making in sales, inventory management, and product optimization.
This solution is intended for use by business managers, sales analysts, restaurant owners, and operations teams who want to gain actionable insights from sales data and improve overall business performance


Tech Stack:
The dashboard was built using the following tools and technologies:
🗄️ Microsoft SQL Server & SSMS – Used for storing, querying, and managing transactional sales data.
📊 Power BI Desktop – Main data visualization platform used for dashboard creation and report development.
📂 Power Query – Used for data cleaning, transformation, and preparation before modeling.
🧠 DAX (Data Analysis Expressions) – Implemented for calculated measures, KPI metrics, dynamic calculations, and business logic.
📈 Data Visualization Techniques – KPI cards, bar charts, donut charts, trend analysis, slicers, and interactive filtering for better storytelling.
📁 File Formats – .pbix for report development and .png for dashboard previews/screenshots.


Data Source:
The dataset used in this project was manually imported into Microsoft SQL Server Management Studio (SSMS) from locally stored sales data files. SQL queries were then written to clean, analyze, and validate the transactional data before connecting it to Power BI for dashboard development.

Data Validation Process:
To ensure data accuracy and consistency (Pizza_Sales_SQL_Queries.docx) -
SQL queries were executed in SSMS to calculate key business metrics such as:
Total Revenue
Total Orders
Average Order Value
Best/Worst Selling Products
Sales by Category and Size
Query outputs and result snapshots were documented and verified before implementing the same logic in Power BI using DAX measures.
The Power BI report results were cross-checked with SQL query outputs to maintain reporting accuracy and business reliability.

Data Workflow:
Local Dataset → SQL Server (SSMS) → SQL Query Validation → Power BI → Interactive Dashboard


Highlights:
• Business Problem
Pizza businesses generate large volumes of transactional sales data daily, but extracting meaningful insights from raw data can be challenging.
Business stakeholders often struggle to answer important operational and strategic questions such as:
Which pizza categories generate the highest revenue?
What are the busiest sales days and months?
Which products are top-performing or underperforming?
What pizza sizes contribute the most to total sales?
How do customer ordering patterns change over time?

Without a centralized analytical solution, identifying trends and making data-driven business decisions becomes inefficient.

• Goal of the Dashboard
The main goal of this dashboard is to provide an interactive analytical platform that:
Monitors overall business performance through key KPIs.
Identifies top and bottom-selling pizza products.
Tracks daily and monthly order trends.
Analyzes customer purchasing behavior by category and pizza size.
Supports business decisions related to inventory planning, product strategy, and sales optimization.


Walkthrough of Key Visuals:
KPI Summary Cards -
Displays high-level business performance metrics including:
Total Revenue
Average Order Value
Total Pizzas Sold
Total Orders
Average Pizzas Per Order
These KPIs provide a quick snapshot of overall sales health and operational performance

Daily Trend for Total Orders (Bar Chart) -
Shows order distribution across days of the week to identify peak business days and customer ordering behavior.
Insight: Orders are highest during weekends, especially Friday and Saturday evenings.

Monthly Trend for Total Orders (Line Chart) -
Visualizes monthly sales fluctuations and seasonal ordering patterns throughout the year.
Insight: Highest order volumes were observed during July and January.

Sales by Pizza Category (Donut Chart) -
Breaks down revenue contribution across pizza categories such as:
Classic
Supreme
Chicken
Veggie
Insight: The Classic category contributes the highest share of total sales and orders.

Sales by Pizza Size (Donut Chart) -
Analyzes revenue contribution by pizza size:
Small
Medium
Large
XL / XXL
Insight: Large-size pizzas generate the maximum sales contribution.

Best & Worst Sellers Analysis -
Dedicated report page highlighting:
Top 5 pizzas by Revenue
Top 5 pizzas by Quantity Sold
Top 5 pizzas by Total Orders
Bottom 5 pizzas across the same metrics
This analysis helps identify high-performing products and products requiring business attention.


Business Impact & Insights:
The dashboard helps identify high-performing pizza categories, peak sales periods, and customer purchasing patterns, enabling better business and inventory planning.
By analyzing top and low-performing products, businesses can optimize menu strategy, improve operational efficiency, and make data-driven sales decisions.


Screenshots:
![Dashboard Preview].(https://github.com/PoonamChikhale/Pizza-Sales-Report/blob/main/Screenshot%20of%20the%20Dashboard1.jpg).

![Dashboard Preview].https://github.com/PoonamChikhale/Pizza-Sales-Report/blob/main/Screenshot%20of%20the%20Dashboard2.jpg).



