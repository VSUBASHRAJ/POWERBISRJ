# POWERBISRJ

Here’s the **complete `README.md` file** you can directly put in your GitHub repo:

---

```markdown
# 📊 Power BI Adventure Works Report

This repository contains an **interactive Power BI dashboard** created using the Adventure Works dataset.  
It demonstrates key Power BI features, including data modeling, DAX calculations, forecasting, and advanced visuals.

---

## 📌 Report Pages

1. **Overview (Full Visuals)**  
   A consolidated dashboard summarizing total sales, profit, orders, and other KPIs.

2. **Profit Analysis**  
   Insights into profitability by product category, subcategory, and geography.

3. **Performance Analysis**  
   Tracks sales and profit trends over time and across regions.

4. **Scatter Chart**  
   Shows relationships between sales, profit, and quantity.

5. **Forecast**  
   Uses Power BI’s forecasting tool to predict future sales trends.

6. **Decomposition Tree**  
   Breaks down metrics like sales and profit into hierarchical dimensions for deeper analysis.

7. **Key Influencers**  
   Identifies the main factors influencing high sales and profit.

---

## 📂 Repository Structure

```


````

---

## 🚀 Getting Started

### 1️⃣ Download Dataset
The dataset is included in the `dataset` folder.  
Alternatively, you can download from Microsoft:  
[Adventure Works Sample Data](https://github.com/microsoft/sql-server-samples/releases/tag/adventureworks)

### 2️⃣ Open Report
Open `AdventureWorks_Report.pbix` in **Power BI Desktop** and refresh data if needed.

### 3️⃣ Explore Pages
Navigate between pages using the tabs at the bottom of the Power BI report.

---

## 📜 DAX Measures Examples
```DAX
Total Sales = SUM(Sales[SalesAmount])
Total Profit = SUM(Sales[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
Sales YoY % = DIVIDE(([Total Sales] - [Total Sales LY]), [Total Sales LY], 0)
Total Orders = COUNTROWS(Sales)
Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
````

---

## 📸 Visual Previews

| Page               | Screenshot |
|--------------------|------------|
| **Overview**       | <img width="1165" height="656" alt="Overview" src="https://github.com/user-attachments/assets/7154b7f2-db0a-445f-9d82-648a2f755e3f" /> |
| **Profit**         | <img width="658" height="251" alt="Profit Chart 1" src="https://github.com/user-attachments/assets/16b1f379-ab88-4729-b0cf-4d72b24c2ab1" /> |
| **Performance**    | <img width="1161" height="652" alt="Performance" src="https://github.com/user-attachments/assets/ba80441c-90a6-4f97-9cf7-81c31959ec32" /> |
| **Scatter Chart**  | <img width="1167" height="655" alt="Scatter Chart" src="https://github.com/user-attachments/assets/65b49b11-bc02-48ee-b040-dcf7eb84e832" /> |
| **Forecast**       | <img width="1169" height="662" alt="Forecast" src="https://github.com/user-attachments/assets/4b33785a-ef02-4fd2-a2a4-2fa24b921339" /> |
| **Decomposition Tree** | <img width="1168" height="656" alt="Decomposition Tree" src="https://github.com/user-attachments/assets/8f73b165-35c0-42d2-bb6f-46d7e2e8d9e8" /> |
| **Key Influencers**| <img width="1169" height="658" alt="Key Influencers" src="https://github.com/user-attachments/assets/7a1c461d-61ac-465b-a8f7-c8cd0271b2f1" /> |



---

