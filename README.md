# Supermarket Sales Performance Analysis

## Project Overview
This project focuses on analyzing supermarket sales data to uncover key trends and performance metrics. The goal is to provide actionable insights into sales performance across different branches, product lines, and over time, visualized through an interactive Power BI dashboard.

## Data Source
The dataset used is "Sales of a Supermarket" from Kaggle.
[Link to Kaggle Dataset](https://www.kaggle.com/datasets/lovishbansal123/sales-of-a-supermarket)
The original data file is included in this repository: `supermarket_sales.csv`

## Tools Used
* **Microsoft Excel:** For initial data review and basic cleaning.
* **Microsoft Power BI Desktop:** For data modeling, creating measures (DAX), and designing interactive dashboards.

## Key Questions Answered
This analysis addresses the following business questions:
1.  What are the total sales and gross income?
2.  Which branches/cities have the highest sales?
3.  Which product lines are most popular or generate the most revenue?
4.  How do sales trends look over time (by month/day)?

## Data Cleaning and Preparation
The dataset was primarily reviewed and found to be quite clean.
* Checked for missing values: **None found.**
* Reviewed data types and consistency: **No major inconsistencies or incorrect types observed.**
* Scanned for outliers and duplicates: **No obvious outliers or duplicate rows identified.**
* _If you did any specific clean-up in Excel, briefly mention it here, e.g., "Minor text cleaning in 'Product line' column."_

## Dashboard Visualizations & Insights

### Overall Dashboard Summary
Below is an overview of the Power BI dashboard, designed to provide a comprehensive view of supermarket sales performance.

![Supermarket Sales Dashboard Overview](screenshots/supermarket_dashboard_overview.png)
*Screenshot of the main dashboard page.*

### Key Insights:

1.  **Total Sales & Gross Income:**
    * Total Sales: **[YOUR TOTAL SALES VALUE HERE, e.g., 322.97K]**
    * Gross Income: **[YOUR GROSS INCOME VALUE HERE, e.g., 15.38K]**
    * These key performance indicators provide an immediate snapshot of the overall business health.

2.  **Sales by Branch/City:**
    * **Insight:** Branch **[YOUR TOP BRANCH HERE, e.g., C]** consistently recorded the highest sales, indicating its strong market presence or customer base.
    * _Briefly describe the visual (e.g., "A bar chart compares sales across branches.")_

3.  **Sales by Product Line:**
    * **Insight:** **[YOUR TOP PRODUCT LINE HERE, e.g., Food and beverages]** is the leading product category in terms of revenue, suggesting high demand or effective pricing for these items.
    * _Briefly describe the visual (e.g., "Another bar chart highlights the performance of various product lines.")_

4.  **Sales Trends Over Time:**
    * **Insight:** Sales show a clear seasonal pattern within the analyzed period. **[YOUR OBSERVATION HERE, e.g., January had the highest sales, followed by a dip in February, and a moderate recovery in March.]** This trend could inform inventory management and marketing strategies for future periods.
    * _Briefly describe the visual (e.g., "A line chart visualizes monthly sales trends, revealing seasonality.")_

## Files in This Repository
* `supermarket_sales.csv`: The original dataset used for this analysis.
* `Supermarket_Sales_Dashboard.pbix`: The Power BI Desktop file containing the data model, measures, and dashboard design.
* `screenshots/supermarket_dashboard_overview.png`: Screenshot of the completed Power BI dashboard.
* `README.md`: This project documentation.

## Future Enhancements (Optional)
* Incorporate customer demographics for more targeted segmentation.
* Perform a profitability analysis by product line or branch.
* Develop a predictive model for future sales forecasting.
* Investigate the impact of payment methods or customer ratings on sales.

---
*This project was created as part of a data analysis portfolio demonstration.*
