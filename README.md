# OLAP Operations on Global Superstore Dataset using Power BI

## 📌 Project Overview

This project demonstrates **OLAP (Online Analytical Processing)** operations such as **Slicing, Dicing, Drill-Down, Drill-Up, and Roll-Up** using the `Global_Superstore2.csv` dataset in **Power BI Desktop**. It includes interactive dashboards for analyzing sales performance across different regions, categories, and time periods.

---

## 📁 Dataset Used

- **Name:** Global_Superstore2.csv
- **Source:** Sample Superstore dataset (standard business dataset)
- **Attributes:**
  - Date fields: `Order Date`, `Ship Date`
  - Dimensions: `Region`, `Country`, `City`, `Category`, `Sub-Category`, `Segment`
  - Measures: `Sales`, `Profit`, `Quantity`, `Discount`

---

## 🎯 Objectives

- Visualize business metrics like Sales and Profit across different dimensions.
- Apply OLAP techniques for deeper data analysis:
  - **Slicing**: Filter data by Region, Category, etc.
  - **Drill-Down/Up**: Analyze data from Category → Sub-Category.
  - **Roll-Up**: Aggregate data at Region or State level.
  - **Time Series Analysis**: Observe trends across months and years.

---

## ⚙️ OLAP Operations Implemented

| OLAP Operation | Implementation Details |
|----------------|------------------------|
| **Slicing**    | Slicers created for `Region`, `Category`, and `Order Date` |
| **Drill-Down** | Bar chart with hierarchy from `Category` → `Sub-Category` |
| **Roll-Up**    | Matrix showing `Sales` and `Profit` by `Region` and `State` |
| **Time Drill** | Line chart showing `Profit` over time with Year/Month drill options |

---

## 🖥️ Dashboard Features

- **Interactive Slicers** for filtering by region, category, and date.
- **KPI Cards** to highlight total Sales, Profit, and Quantity.
- **Line Chart** for time series trend.
- **Column Chart** with drill-down from Category → Sub-Category.
- **Map Visual** for geographical analysis of sales.

---

## 📸 Sample Visuals

- Bar Chart: Sales by Category (Drillable to Sub-Category)
- Line Chart: Profit over Time
- Slicer: Filter by Region
- Table: Sales and Profit Aggregated by Region

---

## ✅ How to Use

1. Download and open the `Global_Superstore_OLAP.pbix` file in Power BI Desktop.
2. Use the slicers to interactively explore the data.
3. Click on visual elements (like bars) to drill into deeper levels of data.

---

## 📤 Export Options

- Dashboard exported as **PDF** for easy sharing.
- `.pbix` file available for editing and enhancement.

---

## 📚 Conclusion

This project showcases how Power BI empowers users to perform deep OLAP-style exploration on business data. The Global Superstore dataset was successfully analyzed using slicing, drill-up/down, and roll-up techniques, resulting in a dynamic, easy-to-navigate dashboard.

---

## 🔖 Author

- **Name:** Dhanashree Sul  
- **Institution:** PCCOE  
- **Tool Used:** Power BI Desktop  
- **Assignment Title:** OLAP Operations Using Power BI

