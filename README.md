# E-Commerce Sales & Profitability Analytics

A hands-on data analytics project where I analyzed historical e-commerce transactional data to track Year-over-Year (YoY) sales growth, category profitability, and customer purchasing patterns across the United States.

## Brief Summary
An end-to-end data project processing nearly 10,000 transaction rows to evaluate company sales performance ($2.30M total revenue) and profit margins across different shipping modes, product segments, and geographical regions.

## Overview
I took a raw multi-year e-commerce sales dataset and transformed it into a clean analytical format to discover hidden business trends. The project focuses heavily on financial performance—calculating exactly which categories and months bring in high revenue versus which ones actually bring in high profits, and tracking how the company's performance scales from 2011 through 2014.

## Problem Statement
For large online retailers, simple revenue tracking hides serious operational issues. High sales volume doesn't always equal high success if shipping costs, massive discounts, or returns eat into the margins. This project answers specific business questions:
1. Which core product categories (Technology, Office Supplies, Furniture) contribute the most to net profit, and where are we losing money?
2. How does performance look year-over-year? Are our total sales growing alongside our profit margins?
3. Which customer segments (Consumer, Corporate, Home Office) and geographical regions represent our highest-value markets?

## Dataset
The dataset consists of 9,994 individual transactional records containing order specifics:
* **Order Details:** Order ID, Order Date, Ship Date, Ship Mode (Standard Class, Second Class, First Class, Same Day).
* **Customer Info:** Customer ID, Name, Segment (Consumer, Corporate, Home Office).
* **Product Data:** Product ID, Category, Sub-Category (Phones, Chairs, Storage, Binders, etc.), Product Name.
* **Geographics:** Country, City, State, Postal Code, Region.
* **Financial Metrics:** Sales, Quantity, Discount, Profit.

## Tools & Technologies
* **Data Processing & Pivot Analysis:** Microsoft Excel (Power Query for structure, Pivot Tables for aggregations)
* **Data Visualization:** Excel Dashboard Design / Power BI
* **Version Control:** Git & GitHub

## Method (How I Built This)
1. **Data Inspection:** Cleaned up numerical inconsistencies in sales and profit records, ensuring that financial fields accurately reflected discounts.
2. **Aggregations & Pivot Architecture:** Created separate analytical tables isolating monthly performance, state-by-state performance, top 5 customer metrics, and high-volume sub-categories.
3. **KPI Calculation:** Tracked macro business metrics across the entire timeline:
   * **Total Sales:** $2,297,200.86 (~$2.30M)
   * **Total Profit:** $286,397.02
   * **Total Quantity Sold:** 37,873 units across 9,994 unique orders.
4. **Dashboard Layout:** Structured the final user interface logically. The top header features quick high-level KPIs, the middle section tracks performance over time (Combo Chart) and category profits (Waterfall Chart), and the bottom layout breaks down data by maps, top customers, and item shares.

## Key Insights
* **Year-over-Year Growth:** The company has scaled significantly. Sales grew from **$484K** in 2011 to **$733K** in 2014, with total profit growing from **$49.5K** to **$93.5K** in that same timeframe.
* **The Furniture Margin Trap:** While Furniture accounts for a massive chunk of total sales volume (**32.3%**), it brings in the *lowest* overall profit ($18.4K). Technology is the real winner, driving **$145.4K** in total profit.
* **Top Sub-Categories:** *Phones* ($330K) and *Chairs* ($328K) are the company's highest revenue-generating product types.
* **Regional Dominance:** California and New York stand out as the absolute highest-performing states for overall sales density.

## Dashboard Output
Here is the complete interactive sales dashboard built from the data:

https://github.com/priyapatel96140/e-commerce-sales-analysis-power-bi-project/blob/main/e-commerce_sales_analysis_dashboard.png

https://github.com/priyapatel96140/e-commerce-sales-analysis-power-bi-project/blob/main/sales-dashboard.png


*Quick stats visible in the dashboard:*
* **Total Sales:** $2.30M
* **Total Profit:** $286.4K
* **Quantity Sold:** 38K items
* Dynamic monthly trend lines tracking revenue spikes every September and November.

## How to Run this Project
1. Download the `.pbix` file
2. Open the file in Power BI Desktop
3. Refresh the dataset if required
4. Interact with filters and visuals
