# 🏢 Sales-Performance-Executive

---

## 📌 Project Overview
An end-to-end Business Intelligence solution that transforms raw relational data from **SQL Server** into an interactive analytical report. 

The project leverages a structured **Data Warehouse Star Schema model** to track enterprise order processing, product quantities, tax and freight costs, and multi-regional revenue from **2011 through 2014**.

---

## 🏗️ Data Architecture & Star Schema Model
The data was imported directly from **SQL Server** and modeled using a classic **Star Schema**:

- **Fact Table:** 
  - FactOrderDetails
- **Dimension Tables:**
  - DimDates
  - DimProducts
  - DimSalesPersons
  - DimTerritories
  - DimStatuses
  - DimShipMethods
- **Measures Table**

---

## 📈 Executive Summary (Key Indicators)
- **Total Orders (#Order):** 31K+
- **Total Order Quantity (#Qty):** 44K+
- **Subtotal Revenue:** $110M
- **Total Due (Gross Revenue):** $123M
- **Freight Expenses:** $3M
- **Total Tax:** $10M

---

## 🔍 Key Features & Visual Insights

1. **Timeline Fulfillment Analysis:**
   - Multi-line chart comparing `#order by Order Date`, `#order by Due Date`, and `#order by Ship Date` across 2011–2014.
2. **Product Volume Metrics:**
   - Bar visual ranking product performance by `#Qty` sold.
3. **Territory Revenue Matrix:**
   - Detailed matrix breakdown comparing regional performance across sales years.
4. **Interactive Navigation & Drill-Through:**
   - Dedicated **Drill-Through page** filtering performance by region groups and dynamic year sliders.

---

## 🛠️ Tech Stack & Tools
- **Database Engine:** SQL Server (Data Source & Import)
- **Data Modeling:** Power BI (Star Schema Architecture & Relationships)
- **DAX & Calculations:** Power BI Measure Tables
- **Visualization:** Power BI 

---
