# 3-Year Sales Performance Dashboard (2022–2024)

This Power BI dashboard analyzes sales data from 2022 to 2024, highlighting key KPIs, product performance, and customer trends.

## 🔑 Key KPIs
- Total Sales: 42M  
- Total Quantity: 17K  
- Unique Orders: 2K  
- YoY Growth: 0.47%

## 🧭 Dashboard Insights
- **Top Customer:** Simran Kaur (3M total sales)  
- **Top Product Category:** Furniture (14M total sales)  
- **Stable YoY Growth:** +0.47%  

## 🗺️ Visuals Included
- Sales trend by year  
- Customer and product category performance  
- Regional sales map  
- AOV (Average Order Value) distribution

## 🧠 SQL Queries Used
```sql
SELECT YEAR(Date) AS Year, SUM(Total_Sales) AS TotalSales
FROM sales
GROUP BY YEAR(Date);
