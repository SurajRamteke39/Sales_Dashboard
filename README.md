# **📊 Sales Distribution Dashboard**

This project presents a comprehensive Sales Performance Dashboard built using Power BI, SQL and Excel, designed to analyze monthly sales trends, regional performance, and customer distribution across various countries.


## **🔍 Overview**

The dashboard helps business analysts and decision-makers explore:

- Monthly sales performance vs targets
- Regional and country-wise sales distribution
- Customer segmentation and product-level insights
- High-performing products and regions


## **📁 Data Source**

The dashboard is powered by a combination of:

- <a href="https://github.com/SurajRamteke39/Sales_Dashboard/commit/6c51b53287462dd8799dc03306ce8794d95d041a">Sales Data</a>: Contains raw sales transactions, customer details, and monthly targets
- Sales Data Stored Procedure.sql: A SQL stored procedure that transforms the raw data for analysis
- Data is processed using SQL and then connected to Power BI for visualization.


## **🛠️ Technologies/Tools Used**

- Microsoft Power BI
- MySQL
- Microsoft Excel
- Data Manipulation, Cleaning, Modeling & Transformation
- DAX & Power Query

  
## **🧾 SQL Setup & Stored Procedure**

Before connecting Power BI to the data, the following steps were performed in SQL Server:

**🔹 Table Creation**
Custom tables were created to organize and clean the data:

  - sales — filtered sales transactions
  - customer — customer details with region info
  - target — monthly sales targets
  - sale_region — enriched sales data with region and country

**🔹 Stored Procedure: [Sales]**

This stored procedure automates the data preparation process:

- Cleans raw sales data by removing invalid entries.
- Filters customer data to include only those with valid region information.
- Loads monthly sales targets for performance comparison.
- Joins sales with customer region data to enable region-wise analysis.
- This ensures that Power BI receives clean, structured data for accurate and insightful reporting.


## **🚀 Getting Started**

To explore:

- Click the link below to open the dashboard in your browser.
- Use filters to view sales by region, month, product, and customer.
👉 - <a href="https://app.powerbi.com/view?r=eyJrIjoiYmZiZGFjMjYtMzY5YS00YWE1LTgxNDgtNjA2MGQxYjZlZDEzIiwidCI6ImFjNDUxYzMzLWU4MGYtNDQwYi1hOTk2LTE0MjJkMzcwY2U2ZSJ9">Sales Dashboard</a>

Note: This dashboard is view-only and requires no setup.


## **📈 Dashboard Features**

- Monthly sales vs target comparison
- Region-wise and country-wise sales breakdown
- Product-level performance insights
- Customer segmentation by geography
- Interactive filters for deep dive analysis

  
## **🖼️ Screenshots**

<img width="1647" height="926" alt="image" src="https://github.com/user-attachments/assets/b01bfc70-ef98-4e56-ba51-09fbc2e9f9da" />


## **🧠 Key Insights & Conclusion**

- Sales targets are consistently met or exceeded in the first half of the year.
- Export regions dominate overall sales volume.
- Certain products and regions show recurring high performance, indicating strong market demand.
- Customer distribution is concentrated toward Indian regions, offering opportunities for localized strategies.
