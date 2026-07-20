Retail Sales Power BI Dashboard

Overview
An interactive sales performance dashboard built on a live PostgreSQL database connection, allowing stakeholders to track net sales, profit, and store performance across regions, states, and product categories in real time.

Tools Used
PostgreSQL (database)
Power BI Desktop (visualization)
DAX (measures & calculations)

Data Source
Store performance dataset — 360 records covering daily sales, transactions, and profit metrics across multiple stores, regions, and product categories.
See data/store_performance_dataset.csv

Key Features
Live connection from Power BI to a PostgreSQL database (not a static file import)
KPI cards for Sum of Net Sales (2.32M) and Sum of Profit (769.31K)
Profit by State bar chart comparing performance across NM, TX, AZ, and CO
Net Sales by Product & Returns chart breaking down sales and returns by category (Grocery, Health, Home, Apparel, Electronics, Sports)
Profit by Store Name chart ranking all 12 stores by profitability
Daily sales detail table with Year/Month/Day drill-down
Interactive Region and State slicers for filtering the entire dashboard

Key Insights
New Mexico (NM) is the top-performing state by profit, notably ahead of Texas, Arizona, and Colorado
Grocery is the highest-selling product category by a clear margin, followed by Health and Home
Rio Grande Market, Lone Star Central, and Valley Sun Retail are the top 3 stores by profit, while Encha... Circle Store trails the rest
Daily net sales in January 2025 ranged roughly between 69K–75K, with January 25 as the peak day shown in the data table

How to Run
Load data/store_performance_dataset.csv into a PostgreSQL database (table: sales)
Open retail_sales_dashboard.pbix in Power BI Desktop
Update the database connection details (server/database name) to match your local setup

Load data/store_performance_dataset.csv into a PostgreSQL database (table: sales)
Open retail_sales_dashboard.pbix in Power BI Desktop
Update the database connection details (server/database name) to match your local setup
