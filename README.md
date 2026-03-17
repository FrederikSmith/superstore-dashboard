# Retail Sales Dashboard – Superstore (Power BI)

A structured Power BI solution built around a clean semantic data model and 
standardised KPI logic. The focus is on reusable measures and consistent business 
definitions rather than ad hoc reporting.

---

## Project Overview

- Multi-page Power BI report tracking sales performance across regions, products 
and customer segments
- KPI-based reporting with year-over-year comparisons
- Built to demonstrate enterprise BI principles at a smaller scale

---

## Data Model

- Star schema with a central sales fact table
- Supporting dimension tables for Date, Product, Customer and Geography
- Clear grain definition to support consistent aggregation across all report pages

---

## KPI & Business Logic

All KPIs are defined as DAX measures to ensure consistent definitions and 
reusability across every page:

- Total Sales
- Total Profit
- Profit Margin Percentage
- AVG Discount Percentage
- Cumulative Sales
- Total Quantity
- YoY Sales Growth Percentage

---

## Performance Considerations

- Measure-based calculations preferred over calculated columns
- Lean model structure to support responsive filtering
- Unnecessary columns removed from the data model to reduce file size

---

## Tools Used

- Power BI
- DAX
- Power Query

---

## Files

- `Superstore_Report.pbix` Power BI dashboard file
- `Screenshots/` Static images of each report page and data model view
- `Data/` Original Excel dataset used in the report (fictional data)

---

## Related Projects

For a more complete end to end project combining SQL, Python and Power BI see my 
logistics dashboard:

[Logistics Delivery Performance Dashboard](https://github.com/FrederikSmith/logistics-dashboard)
