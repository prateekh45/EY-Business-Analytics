# EY-Business-Analytics
Comprehensive Power BI dashboard and analysis for EY Business Analytics, dissecting 6 months of sales and profit data across categories, regions, and segments.

# 📈 EY Business Analytics: Sales and Profit Performance Dashboard

## 🌟 Project Overview

This project focuses on a comprehensive analysis of six months of sales data (January - June) using Power BI. The goal was to identify key performance drivers, regional and product-level strengths and weaknesses, and provide data-driven recommendations to improve overall profitability and operational efficiency.

The analysis provides a detailed breakdown across **Region, Segment, Category, State,** and **Sub-Category**.

## 🛠️ Tools and Technologies

* **Primary Tool:** Power BI (for Visualization, Data Modeling, and DAX)
* **Data Source:** Simulated Sales Data (e.g., CSV, Excel)
* **Concepts:** ETL, Data Modeling (Star Schema), KPI Definition, Hypothesis Testing.

## 🎯 Key Performance Indicators (KPIs)

| Metric | Value | Insight |
| :--- | :--- | :--- |
| **Sum of Sales** | $160.99K | Total revenue generated over the 6-month period. |
| **Sum of Profit** | $15.02K | Total profit earned. |
| **Gross Profit Margin** | 9.32% | The margin is relatively low, indicating potential issues with pricing, cost of goods, or heavy discounting. |
| **Best Performing Month** | June | Highest sales and profit achieved. |
| **Best Segment** | Consumer | Highest profit contributor (\$7.2K, 47.90% of total profit). |

## 🚀 Key Findings and Insights

### 1. Profitability Drivers
* **Most Profitable Category:** **Office Supplies** (53.37% of total profit, $8.01K).
    * *Insight:* Despite lower sales volume than Technology, high margins and high discounts (23.47% in the Central region) are used effectively to drive profitability in this segment.
* **Highest Profit Product:** **Phones** (Sub-Category) generated the highest profit ($5.17K) and sales ($19.08K).

### 2. Regional Disparities
* **Top Performer:** **South** region leads significantly in both Sales ($67K) and Profit ($7.1K).
* **Area of Concern:** **East** ($0.7K) and **Central** ($1.1K) regions show extremely low profit, contributing only 12% combined to the total profit, despite contributing a larger share of sales.
    * *Hypothesis:* This suggests potential issues with supply chain, logistics, higher operational costs, or intense competition in these areas.

### 3. Segment and Monthly Volatility
* **Consumer Dominance:** The **Consumer** segment is the most important, contributing 43.37% of Sales and 47.90% of Profit.
* **Profit Loss:** The **Home Office** segment experienced a rare **profit loss** (-\$0.4K) in **March**, indicating a potential one-time error, heavy inventory clearance, or a failed promotional event.

## 💡 Recommendations for Business Improvement

Based on the data, the following three actions are recommended to address key weaknesses and capitalize on existing strengths:

1.  **Strategic Intervention in East & Central Regions:** Launch a focused investigation into the cost structures (logistics, transportation, warehousing) and local competition in the East and Central regions. The gross margin is unsustainably low here.
2.  **Optimize Office Supplies Discount Strategy:** Since Office Supplies is the most profitable category, analyze the specific sub-categories (e.g., Binders) receiving the highest discounts in the **Central** region. This discount strategy may be replicable in other high-cost regions to maintain profit volume.
3.  **Capitalize on Consumer Segment:** Double down on marketing and product development within the **Consumer** segment, particularly for high-value items like **Phones**, as this segment is the primary engine for both sales and profit.

## 📁 Repository Structure

| Folder/File | Description |
| :--- | :--- |
| `1_Project_Documentation/` | Contains detailed business case, data source notes, and the full analysis summary. |
| `2_Data_Modeling_and_Analysis/` | Key technical assets including the data model schema and core DAX measures. |
| `3_Power_BI_Report/` | The final Power BI file (`.pbix`) and screenshots of all dashboard pages. |
| `README.md` | This document, summarizing the project and key findings. |

***

*To view the interactive dashboard, please download and open the `Sales_Performance_Dashboard.pbix` file using Power BI Desktop.*
