# Adidas US Sales Performance Analysis

## Overview

This project provides an in-depth analysis of Adidas US sales performance for 2020 and 2021. Using Power BI, the report explores product sales, retailer performance, sales methods, and regional growth. It offers insights into key trends, growth opportunities, and areas where business strategies can be optimized.

## Objectives

- Analyze **product performance** by region, retailer, and sales method.
- Evaluate the **growth trends** in sales and units sold across different sales methods (in-store, online, outlet).
- Assess **retailer performance** and identify opportunities for growth.
- Identify **high-growth regions** and assess how geography impacts profitability.

## Features

### **Home Page**
![HomePage](https://github.com/user-attachments/assets/4bb6892e-e6de-4155-83f7-7a6859f80668)

- **Page Navigation Button**: Navigate between different sections of the report with ease.
- **Region Slicer**: Filter the report based on specific regions, allowing for targeted performance analysis.

### **Adidas Product Analysis**
![image](https://github.com/user-attachments/assets/6b99888c-6755-4e18-8272-d845d6106c1d)

- **Retailer Slicer**: Filter the analysis by different retailers to compare performance.
- **Year and Month Slicer**: Adjust the timeframe to analyze sales for specific years and months.
- **Product Slicer (at the page bottom)**: Filter to focus on specific products.
- **Product Image and Name**: Display the product image and name for easy identification.
- **Average Price**: View the average price of each product.
- **Bar Chart - Sales by Sales Method**: Compare sales across different methods (in-store, online, outlet).
- **Cards**:
  - **Total Units Sold**: Show the total number of units sold for the selected product(s).
  - **Units Sold Month-over-Month (MOM)**: Track month-over-month growth or decline in units sold.
  - **Total Sales**: Display total revenue for the selected product(s).
  - **Total Sales Month-over-Month (MOM)**: Show month-over-month sales growth or decline.
- **Area Chart**: Visualize sales and units sold trends over time.

### **Adidas Sales Overview for Deep Insight**
![DeepInsight](https://github.com/user-attachments/assets/72c88a87-92ec-41b2-8436-3953e96aaa66)

- **Sales Method Slicer**: Filter by sales method to evaluate the contribution of different channels.
- **Year and Month Slicer**: Adjust for year and month-specific insights.
- **Cards for Key Metrics**: Display total sales, total units sold, profit, and transaction count.
- **Bar Charts**:
  - **Sales by Retailer**: Evaluate the performance of each retailer.
  - **Sales by Product**: Breakdown of sales data by product.
  - **Sales by Region**: Visualize sales across different regions.
  - **Total Transactions by Region**: Track the number of transactions by region.
- **Map of Sales by State**: Visualize sales distribution across states.
- **Area Chart of Sales by State**: Analyze sales trends by state over time.

### **Adidas Trend Analysis**
![Trend Analysis](https://github.com/user-attachments/assets/d310b7bc-0226-40d4-be5d-0a37a0dd83fe)

- **Sales Method Slicer**: Filter by sales method to evaluate performance by channel.
- **Year and Retailer Slicer**: Filter data by year and retailer for trend-specific insights.
- **Cards for Key Metrics**: Show total sales, total units sold, profit, and transaction count.
- **Table Showing States, Sales, and Sales Year-over-Year (YOY)**: Present sales and YOY comparisons for each state.
- **Line Chart - Profit MOM vs Sales MOM**: Compare month-over-month changes in profit versus sales.
- **Line Chart - Units Sold MOM vs Sales MOM**: Track month-over-month trends in units sold and sales revenue.
- **Line Stacked Column Chart**:
  - **Profit vs Average Margin**: Show the relationship between profit and average margin.
  - **Total Sales vs Profit**: Compare total sales to profit for each product or region.

## Data

This report uses the following datasets to analyze Adidas US sales performance:

### **Sales Data**
The **Sales Data** dataset contains key information on sales transactions, including retailer performance, product sales, and operational metrics.

- **Retailer**: The name of the retailer or store selling the product.
- **Retailer ID**: A unique identifier assigned to each retailer.
- **Invoice Date**: The date the transaction occurred.
- **Location Key**: A unique identifier for the location where the sale took place.
- **Product**: The name or identifier of the product sold.
- **Price per Unit**: The price of one unit of the product.
- **Units Sold**: The number of units sold in the transaction.
- **Total Sales**: The total revenue generated from the sale.
- **Operating Profit**: The profit generated from operations, excluding non-operating income and expenses.
- **Operating Margin**: The percentage of revenue that is operating profit.
- **Sales Method**: The method through which the sale was made, such as in-store, online, or outlet.

### **Product Data**
The **Product Data** dataset contains details about each product sold.

- **Product Name**: The name or identifier of the product.
- **Product Image**: The URL of the product image for display in the report.

### **Location Data**
The **Location Data** dataset provides geographic details for each sale location.

- **Region**: The broader geographical region in which the sale occurred.
- **State**: The state where the sale occurred.
- **City**: The city of the sale location.
- **Location Key**: A unique identifier for the location, which links the sales data to the corresponding location.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/adidas-sales-analysis.git
   ```

2. **Set up Power BI:**
   - Download and install [Power BI Desktop](https://powerbi.microsoft.com/downloads/).
   - Open the `.pbix` file from the repository in Power BI to interact with the dashboard.

3. **Data Preparation:**
   - Ensure your dataset is structured as specified in the [Data](https://github.com/AbdurRahman-Olaniyan/Adidas-US-Sales-Analysis/tree/main/Data) folder. You can update it as needed to match the format.

## Usage

1. **Open the Power BI Report**: 
   - Navigate to the folder containing the `.pbix` file and open it in Power BI Desktop.

2. **Interact with the Dashboard**:
   - Use the slicers for **Region**, **Retailer**, **Year**, **Month**, and **Product** to filter the data.
   - Hover over visual elements for tooltips and detailed metrics like total units sold, revenue, and profit.
   - Explore the different pages to analyze product performance, retailer contributions, and regional trends.
