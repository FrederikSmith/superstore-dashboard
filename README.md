# 📊 Retail Sales Dashboard – Superstore (Power BI)

This project demonstrates a structured Power BI solution based on a clean data model and standardized KPI logic.

The focus is on **data modeling, reusable measures, and clear business definitions**, rather than ad hoc reporting.

---

## 📌 Project Overview
- Multi-page Power BI report
- Sales performance across regions, products, and customer segments
- KPI-based reporting with year-over-year comparisons

---

## 🗂️ Data Model
- Star schema with a central sales fact table
- Supporting dimension tables (Date, Product, Customer, Geography)
- Clear grain definition to support consistent aggregation

---

## 📐 KPI & Business Logic
The report is built around standardized measures to ensure consistent definitions across all pages:
- Sales
- Profit
- Margin
- Year-over-Year growth

All KPIs are defined as DAX measures to support reuse and maintainability.

---

## 🧮 DAX Measures
- AVG Discount Percentage
- Cumulative Sales
- Profit Margin Percentage
- Total Profit
- Total Quantity
- Total Sales
- YoY Sales Growth Percentage

Measures are reused across visuals to ensure consistent business logic.

---

## ⚡ Performance Considerations
- Measure-based calculations preferred over calculated columns
- Lean model structure to support responsive filtering
- Avoidance of unnecessary columns in the data model

---

## 🛠️ Tools Used
- Power BI
- DAX
- Power Query

---

## 📁 Files
* `Superstore_Report.pbix` – Power BI dashboard file
* `Screenshots/` – Static images of each report page and model view
* `Data/` – Includes the original Excel dataset used in the report (fictional)
