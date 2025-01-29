# Amazon Sales Dashboard

![image](https://github.com/user-attachments/assets/f4e36510-7b05-4b02-8945-130036f89b46)

## Overview
The **Amazon Sales Dashboard** is a comprehensive visualization tool designed to analyze and track sales performance, orders, and shipment status over time. This dashboard provides valuable insights into key business metrics, helping sellers and businesses make informed decisions.

## Features and Visual Descriptions

### 1. Total Sales, Orders, and Quantity Overview
- **Visual Type**: KPI Cards
- **Description**: Displays three key performance indicators: total sales (₹78.59M), total orders (128,975), and total quantity sold (116,649). These KPIs provide a quick snapshot of overall business performance.

![image](https://github.com/user-attachments/assets/a44f8ebc-ff2c-47c4-bcbc-f240eb8e3d65)

### 2. Total Sales Trend
- **Visual Type**: Line Chart
- **Description**: This visual represents the total sales trend over several months, showing fluctuations in revenue. Peaks and dips in sales data help in understanding seasonal variations and business cycles.

![image](https://github.com/user-attachments/assets/06e61814-066a-4f77-a925-0c362c92ea06)

### 3. Category-wise Sales
- **Visual Type**: Bar Chart
- **Description**: Shows revenue distribution across different product categories such as Set, Kurta, Western Dress, etc. The height of each bar indicates the sales volume for that category, helping in identifying top-selling products.

![image](https://github.com/user-attachments/assets/9f42f422-8ef9-48bb-adee-e1303d59ffc1)

### 4. Shipping Status Analysis
- **Visual Type**: Treemap
- **Description**: A hierarchical treemap visualizes the shipping status of orders, categorizing them as shipped, delivered, canceled, etc. Larger blocks represent higher volumes in respective categories.

![image](https://github.com/user-attachments/assets/4d59bd27-60a2-4baa-985a-2c5eaeed478b)

### 5. B2B vs. Non-B2B Sales
- **Visual Type**: Pie Chart
- **Description**: A pie chart compares the proportion of B2B vs. Non-B2B sales. The chart reveals that 99.25% of sales come from non-B2B transactions, highlighting the dominance of individual buyers over bulk purchases.

![image](https://github.com/user-attachments/assets/0801fd9d-f9d3-4b8c-8a0a-eb2b5f7612b4)

### 6. Ship Service Level
- **Visual Type**: Donut Chart
- **Description**: This chart breaks down total sales based on shipping service levels (Expedited vs. Standard). A significant portion of sales (69.07%) are fulfilled via standard shipping, while the rest (30.93%) use expedited shipping.

![image](https://github.com/user-attachments/assets/6d0eff2c-cc7c-4088-ab19-172f050c00a3)

### 7. Order Fulfillment
- **Visual Type**: Stacked Bar Chart
- **Description**: Displays the proportion of orders fulfilled by Amazon vs. merchants across different product categories. This allows businesses to evaluate fulfillment performance and optimize logistics.

![image](https://github.com/user-attachments/assets/7b05acbe-cf61-49de-90a6-5f3159bd1a70)

## Data Insights
- The highest sales category is **Set** with ₹39M in revenue.
- The majority of shipments (78K) are successfully shipped, while a portion is still in the delivery process or canceled.
- The majority of sales (99.25%) come from Non-B2B transactions.
- Standard shipping is the most commonly used service level.
- Amazon fulfills a significant portion of orders compared to merchants.

## Technologies Used
- **Power BI**: For data visualization and report creation.
- **SQL**: To extract and manipulate sales data.
- **DAX Formulas**: To calculate KPIs.
- **Power BI Query Editor**: To transform and clean the data.
- **Field Parameters**: To switch dynamically between KPI-based visuals.

## How to Use
1. Load the dataset into Power BI.
2. Ensure that data sources are correctly linked to the dashboard.
3. Apply filters (Category, Status, Ship-State) to customize the insights.
4. Analyze key sales trends and optimize business strategies accordingly.

## Future Enhancements
- Integration with real-time sales data.
- More interactive filtering options.
- AI-driven predictive sales analysis.
