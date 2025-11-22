# 📊 Task 6 – Sales Trend Analysis Using SQL

## 📌 Objective
Analyze monthly revenue and order volume from the online sales dataset using SQL aggregation functions.

---

## 🗂 Dataset Used
**File:** Online Sales Data.csv  
Contains:
- Transaction ID
- Date
- Product Category
- Product Name
- Units Sold
- Unit Price
- Total Revenue
- Region
- Payment Method

---

## 🧠 What I Did
- Imported the CSV file into MySQL Workbench  
- Extracted **Year** and **Month** using the EXTRACT() function  
- Calculated:
  - **Monthly Revenue** → SUM(Total_Revenue)
  - **Order Volume** → COUNT(Transaction_ID)
- Grouped data by Year and Month
- Sorted results using ORDER BY
- Exported and visualized monthly revenue trend
- Generated output PDF with SQL + chart
