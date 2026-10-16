# Sales Performance & Business Insights Dashboard

## Overview
An interactive sales analytics dashboard built using Microsoft Power BI to explore sales performance, profitability, order trends, product categories, regions, and customer segments.

## Objective
To practice transforming a retail sales dataset into an interactive dashboard that supports business performance monitoring and exploratory analysis.

## Tools and Technologies
- Microsoft Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel

## Dataset
This project uses the Sample Superstore dataset, which includes retail order information such as order dates, product categories, sales, profit, discounts, regions, and customer segments.

The dataset is used for educational and portfolio purposes. Results describe the sample data and should not be interpreted as the performance of a real employer or business.

## Dashboard Features
- KPI cards for Total Sales, Total Profit, and Total Orders
- Sales and profit comparisons by product category
- Monthly sales trend
- Region slicer for interactive filtering
- Segment slicer for customer-segment analysis
- Discount-versus-profit scatter plot
- Profit Margin and Average Order Value measures

## Data Preparation
Inspected the dataset in Power Query, checked column data types and data quality indicators, and prepared the data for visualization.

## KPI Definitions
- **Total Sales:** Sum of the Sales column.
- **Total Profit:** Sum of the Profit column.
- **Total Orders:** Distinct count of Order IDs.
- **Profit Margin:** Total Profit divided by Total Sales.
- **Average Order Value:** Total Sales divided by distinct order count.

Note: Average Order Value is calculated here using total sales divided by distinct orders. Depending on the dataset's definition of an order, this is a useful project-level KPI rather than a universal accounting definition.

## Key Findings
Add three findings after examining the dashboard. Include the relevant categories, regions, time periods, and values where available. Do not insert assumed or invented results.

1. **Category performance:** [Add your verified finding.]
2. **Regional performance:** [Add your verified finding.]
3. **Discount and profitability:** [Add your verified finding.]

## Files
- `Sales_Performance_Insights.pbix` — Power BI report file.
- `sales_dashboard.png` — Screenshot of the completed dashboard.

## How to View the Project
1. Download the PBIX report from this repository.
2. Open it using Power BI Desktop.
3. Interact with the Region and Segment slicers and explore the charts.

## Learning Outcomes
- Practiced data inspection and preparation with Power Query.
- Created business KPIs using DAX.
- Designed interactive visualizations and slicers.
- Explored sales and profitability patterns in sample retail data.

## Disclaimer
This is an educational portfolio project built using sample data. The findings are limited to the dataset and do not establish causation.
