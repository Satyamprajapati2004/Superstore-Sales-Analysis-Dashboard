Retail Sales Performance Analysis Dashboard
📌 Project Overview
This project provides a comprehensive analysis of retail sales performance using the Sample-Superstore dataset. The goal was to transform raw data into actionable business insights by leveraging SQL for data cleaning and Power BI for advanced visualization.
Dashboard Preview
![Dashboard](dashboard.png)


🛠️ Tech Stack
Data Cleaning & Transformation: SQL (VS Code)

Data Visualization: Power BI Desktop

Dataset: Sample-Superstore (CSV/Excel)

📂 Project Structure
sales_dashboard.pbix: The primary Power BI file containing interactive dashboards and KPI reports.

db_dump.sql: Comprehensive SQL script detailing the data cleaning, null handling, and data standardization process.

Data/: Contains the raw dataset used for the analysis.

🧹 Data Engineering (SQL)
In this phase, I focused on ensuring data integrity and optimizing the dataset for Power BI:

Standardization: Converted Order Date into a proper Date format for time-series analysis.

Null Handling: Used COALESCE and UPDATE statements to manage missing values in critical columns like Postal Code.

Business Logic: Implemented CASE statements to categorize orders into 'Profit' or 'Loss' segments.

📊 Dashboard Key Features
Executive Summary: Top-level KPIs for Total Sales ($2.30M), Total Profit, and Order Count.

Category Analysis: Breakdown of sales by category showing Technology as the leading revenue generator ($0.83M).

Geographical Trends: Analysis of order distribution across major cities like New York and Los Angeles.

Interactive Slicers: Dynamic filtering by Region and Category to drill down into specific market segments.

💡 Key Insights
Top Performer: The Technology category accounts for the highest share of revenue.

Regional Performance: Identified specific sales trends in the South Region that require strategic intervention to match the growth of the Western and Eastern regions.
