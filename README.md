# E-Commerce-Sales-Analysis-Dashboard
Power BI dashboard analysing 10,000+ global e-commerce orders across markets, categories, and regions - KPI cards, decomposition tree, and dynamic slicers.
# Global E-Commerce Sales Dashboard — Power BI

## Overview
An interactive 2-page Power BI dashboard built on a global orders dataset (~10,000+ records) covering sales performance across international markets, product categories, shipping modes, and customer segments.

## Dashboard Pages

### Page 1 — Sales Overview
- KPI Cards: Total Sales, Total Profit, Total Quantity, Shipping Cost, Total Discount
- Pie Chart: Sales distribution by Market (APAC, EU, US, LATAM, Africa)
- Column Chart: Sales by Product Category (Furniture, Office Supplies, Technology)
- Funnel Chart: Sales by Ship Mode (Standard, Second Class, First Class, Same Day)
- Donut Chart: Sales split by Country
- Area Chart: Profit and Discount trends by Category
- Slicers: Market filter and Category filter applied across all visuals

### Page 2 — Regional Deep Dive
- Decomposition Tree: Profit broken down by Region and Product Name
- Ribbon Chart: Segment distribution across Regions over time
- Donut Chart: Country-level sales breakdown
- Location Cards: Country, State, City reference cards

## Tools Used
- Power BI Desktop
- Dataset: Global Superstore Orders (provided, pre-cleaned)

## Key Visuals
![Dashboard Preview](images/page1_preview.png)

## Status
> **Note:** This is an initial build. An enhanced version with Python-based data cleaning, DAX measures, and business recommendations is currently in development.

## What I Learned
- Building multi-page dashboards with cross-page slicer interactions
- Using decomposition trees for root cause analysis of profit drivers
- Choosing the right chart type for categorical vs trend vs part-to-whole data
- Structuring a dashboard layout for business readability
