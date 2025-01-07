# Swiggy Instamart Analysis

## Project Overview
This project, titled **Swiggy Instamart Analysis**, focuses on analyzing grocery sales data using advanced Excel techniques to uncover customer behavior insights, track sales trends, and optimize product offerings. The dataset used for this project contains details about products, outlets, and sales performance, enabling the creation of dynamic dashboards and actionable insights.

## Dataset Description
The dataset, named `Grocery Sales`, is a `.CSV` file with the following columns:

1. **Item_Identifier**: Unique ID for each product.
2. **Item_Weight**: Weight of the product.
3. **Item_Fat_Content**: Indicates whether the product is low fat or not.
4. **Item_Visibility**: Percentage of the display area allocated to the product.
5. **Item_Type**: Category or type of product.
6. **Item_MRP**: Maximum Retail Price of the product.
7. **Outlet_Identifier**: Unique ID for each store.
8. **Outlet_Establishment_Year**: Year the store was established.
9. **Outlet_Size**: Size of the store (small, medium, or large).
10. **Outlet_Location_Type**: Type of city or region (urban, suburban, or rural).
11. **Outlet_Type**: Store type (grocery store or supermarket).
12. **Item_Outlet_Sales**: Total sales of the product in a specific store.

## Steps Taken
1. **Data Cleaning**:
   - Removed duplicates and handled missing values.
   - Filled `Item_Weight` using averages for each `Item_Type`.
   - Standardized text values in the `Item_Fat_Content` column.
   - Filled missing `Outlet_Size` values using pivot tables.

2. **Data Transformation**:
   - Renamed `Item_Outlet_Sales` to `_Total_Sales` for better clarity.
   - Created new metrics such as product ratings based on sales.

3. **Data Visualization**:
   - Designed pivot tables for analysis.
   - Created a dynamic and interactive dashboard to visualize insights.

4. **Dashboard Design**:
   - The Excel file contains the following sheets:
     - **Original Dataset**: Raw data.
     - **Processed Dataset**: Cleaned and transformed data.
     - **Rough Sheet**: Pivot tables and practice work.
     - **Dashboard**: Interactive visualizations.

## Business Requirements
The analysis addresses the following objectives:
- Understand sales performance and trends.
- Evaluate customer preferences and product demand.
- Optimize inventory distribution and store layouts.

## KPIs Implemented
1. **Total Sales**: Overall revenue generated.
2. **Average Sales**: Average revenue per sale.
3. **Number of Items Sold**: Count of unique items sold.
4. **Average Rating**: Customer satisfaction metric for products.

## Charts and Visualizations
1. **Total Sales by Fat Content**: Donut Chart
2. **Total Sales by Item Type**: Bar Chart
3. **Fat Content by Outlet for Total Sales**: Stacked Column Chart
4. **Total Sales by Outlet Establishment Year**: Line Chart
5. **Sales by Outlet Size**: Donut/Pie Chart
6. **Sales by Outlet Location**: Funnel Map
7. **All Metrics by Outlet Type**: Matrix Card

## Insights Derived
- Products with low-fat content had higher sales in certain regions.
- Supermarkets outperformed grocery stores in terms of total sales.
- Urban outlets contributed significantly to overall revenue.
- Larger outlet sizes correlated with higher sales volumes.

## Future Scope
- Expand the analysis to include customer feedback and demographics.
- Incorporate additional KPIs such as profit margins and cost analysis.
- Use Power BI or Tableau for further visualization enhancements.

## How to Use
1. Download the project files from this repository.
2. Open the Excel file and explore the sheets:
   - Original Dataset
   - Processed Dataset
   - Rough Sheet
   - Dashboard
3. Use slicers and filters in the dashboard to interact with the data and gain insights.

## Tools and Technologies
- **Microsoft Excel**: For data cleaning, transformation, and visualization.
- **Pivot Tables**: For summarizing and analyzing data.
- **Dynamic Charts**: For creating interactive visualizations.

## Acknowledgments
- Dataset Source: [Kaggle](https://www.kaggle.com)

Feel free to explore, contribute, or provide feedback!

