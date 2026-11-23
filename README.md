# Car Sales Analytics Dashboard | Tableau & SQL
# Overview

An end-to-end Car Sales Analytics project developed using Tableau and SQL to monitor dealership sales performance, vehicle demand, pricing trends, dealer performance, and regional sales distribution.

The project combines interactive Tableau dashboards with SQL-based business analysis to help dealerships track KPIs, identify growth opportunities, and make data-driven sales decisions.

# Project Workflow

Raw Car Sales Data
↓
SQL Analysis
↓
KPI Validation & Reporting
↓
Tableau Dashboard
↓
Business Insights
# Tools & Technologies
Tableau
SQL Server / SQL
Excel Dataset
Data Visualization
Business Analytics
Repository Structure

Car-Sales-Analytics/
│
├── Dataset/
│ └── Car_Sales_Data.xlsx
│
├── BRD/
│ └── Business_Document.docx
│
├── SQL Queries/
│ └── SQL_Queries_For_Car_Sales.docx
│
├── Tableau Dashboard/
│ └── Car_Sales_Dashboard.twb
│
├── Assets/
│ ├── Car_Sales_Background.jpg
│ └── Dashboard_Preview.png
│
└── README.md
# Business Objectives
Monitor total sales performance.
Track YOY growth in sales and vehicles sold.
Analyze vehicle pricing trends.
Evaluate dealer and regional performance.
Understand customer preferences by body style, color, and transmission.
Identify top-selling car manufacturers and models.
Key KPIs
KPI	Value
YTD Total Sales	$371.19M
YTD Average Price	$27.99K
YTD Cars Sold	13,261
YOY Sales Growth	23.59%
YOY Cars Sold Growth	24.57%
YOY Avg Price Growth	-0.79%
Dashboard Analysis
Sales Performance
Weekly YTD Sales Trend
YTD Total Sales Performance
YOY Growth Analysis
Average Vehicle Price Analysis
Product Analysis
Sales by Body Style
Sales by Vehicle Color
Company-wise Sales Performance
Top Selling Models
Dealer Analysis
Sales by Dealer
Sales by Dealer Region
Geographic Sales Distribution
Customer Preference Analysis
Body Style Preferences
Transmission Preferences
Vehicle Color Preferences
# SQL Analysis

The project includes SQL queries developed to answer core business questions:

Highest revenue-generating car company
Top 10 selling car models
Highest-performing dealer
Best-performing dealer region
Most preferred body style
Automatic vs Manual vehicle preference
Average selling price by company
Premium pricing vs sales volume analysis
Example Query
SQL
SELECT Company,
SUM(Price) AS Total_Revenue
FROM CarSales
GROUP BY Company
ORDER BY Total_Revenue DESC;
Key Insights
Generated $371.19M in YTD sales revenue.
Sold 13,261 vehicles, reflecting strong dealership performance.
Vehicle sales increased by 24.57% YOY, indicating growing market demand.
Average vehicle price remained stable at approximately $28K.
SUV body style contributed the highest sales revenue among vehicle categories.
Pale White and Black emerged as the highest-revenue vehicle colors.
Certain dealer regions consistently outperformed others, creating opportunities for regional strategy optimization.
Automatic transmission vehicles represented the majority of total vehicle sales.
Recommendations
Dealer Network Optimization
Replicate sales strategies from top-performing dealer regions.
Provide support and targeted campaigns for underperforming dealerships.
Product Strategy
Maintain higher inventory levels for top-selling body styles and models.
Focus promotions around high-demand vehicle segments.
Pricing Strategy
Review pricing for segments with declining average selling prices.
Use premium packages and financing offers to improve margins.
Customer Preference Strategy
Align inventory planning with customer demand for popular colors and transmission types.
Promote top-performing vehicle models through targeted marketing campaigns.
Revenue Growth
Increase focus on high-performing manufacturers and dealer networks.
Develop upselling opportunities for premium vehicle categories.
Key Skills Demonstrated
Tableau Dashboard Development
SQL Querying
KPI Reporting
Sales Analytics
Data Visualization
Business Intelligence
Trend Analysis
Performance Reporting
Customer Preference Analysis
Executive Summary

This project analyzed $371.19M in vehicle sales revenue across 13,261 vehicles sold, providing visibility into sales performance, pricing trends, dealer effectiveness, regional contribution, and customer buying preferences. The analysis highlighted strong YOY growth, high-performing dealer regions, popular vehicle categories, and opportunities for inventory optimization, pricing improvements, and revenue growth.

# Author

Shubham Kumar Jha
Aspiring Data Analyst | Power BI | Tableau | SQL | Excel | Python


Project Type: Sales Analytics • Tableau Dashboarding • SQL Analysis • Business Intelligence
