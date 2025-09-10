# PBI-Dashboard
# SN Corp Dashboard

## Overview
This Power BI dashboard provides a comprehensive analysis of SN Corp's sales performance. It allows users to gain a detailed understanding of key business metrics, including sales, cost, and profit, and to analyze trends across different regions, product sub-categories, and time periods.

## Key Features
- **High-Level KPIs:** Track total sales, cost, and profit at a glance.
- **Dynamic Filtering:** Interactively filter data by `Order Date` and `Ship Mode` to customize your analysis.
- **Detailed Customer View:** The "Customer Name" table provides a detailed breakdown of performance for individual customers.
- **Geographic Analysis:** The map visualizes sales performance across different countries, helping to identify top-performing regions.
- **Performance by Sub-Category:** A bar chart breaks down sales, profit, and quantity by product sub-category to pinpoint best-selling items.
- **Time-Based Trends:** A line chart shows the total number of orders over time, allowing for easy identification of trends and seasonality.
- **Regional Breakdown:** The pie chart provides a clear view of product quantity distribution by region.

## Data & Logic
- **Data Source:** This dashboard uses a snapshot of the SN Corp Sales data.
- **Measures:**
    - `Profit` is a calculated measure: `Sum of Sales - Sum of Cost`.
    - `Count of Order ID` is a distinct count of the `Order ID` field.

## How to Use
1.  Open the dashboard in Power BI.
2.  Use the `Order Date` and `Ship Mode` slicers on the left to filter the data.
3.  Click on any data point within a visual (e.g., a region on the pie chart or a country on the map) to cross-filter all other visuals on the dashboard.
4.  Hover over any visual to see detailed information via tooltips.

## Contact
For any questions, feedback, or issues with the dashboard, please contact:
- **Author:** Dakshita Juyal
- **Email:** dakshitajuyal04@gmail.com

---
*Last Updated: September 10, 2025*
