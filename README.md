# Amazon Prime Sales Performance Dashboard 📊

## 📝 Project Overview
This project is an end-to-end **Data Analysis and Business Intelligence** solution developed using **Power BI**. It provides a comprehensive analysis of Amazon Prime's sales performance, customer ordering behavior, and regional revenue distribution between the years **2005 and 2008**. The dashboard is designed to help stakeholders identify growth opportunities and track key performance indicators (KPIs).

## 💡 Key Insights & Findings
* **Top Performing Category:** **Bikes** generated the highest revenue, contributing approximately **$95M** to the total sales, despite having fewer order counts compared to Accessories.
* **Volume vs. Value:** **Accessories** had the highest number of orders (41K) but generated significantly lower revenue compared to Bikes, indicating they are high-volume, low-margin products.
* **Peak Performance Year:** The year **2007** witnessed a massive spike in both sales (**$42M**) and order volume (**51K orders**).
* **Regional Leader:** The **Southwest** territory is the most profitable region, generating **$24M** in sales, followed by Canada and the Northwest.

## 🎯 Key Performance Indicators (KPIs)
The dashboard tracks the following top-level metrics:
* **Total Sales:** $109.8M
* **Total Due:** $123.2M
* **Total Orders:** 121K
* **Total Customers:** 19K
* **Max Quantity per Product:** 44

## 🛠️ Technical Stack & Data Modeling
* **Tool:** Power BI Desktop
* **Data Processing:** Power Query (ETL processes to clean and shape the data).
* **Data Modeling:** Built a robust **Star Schema** to optimize performance, connecting a central Fact table (`FactOrderDetails`) with multiple Dimension tables:
  * `DimProducts` (Categories, Subcategories)
  * `DimTerritories` (Regions, Countries)
  * `DimDates` (Time Intelligence)
  * `DimSalesPersons`, `DimShipMethods`, `DimStatuses`
* **Calculations:** Utilized **DAX (Data Analysis Expressions)** to create custom measures for dynamic aggregation (e.g., calculating Year-over-Year growth, Total Sales, and dynamic filtering).

## 📊 Visualizations Used
* **Card Visuals:** For quick KPI scanning.
* **Clustered Column Charts:** To compare Sales by Category, Territory, and Year.
* **Line Charts:** To analyze the trend of Orders over time (Order Date, Due Date, Ship Date).
* **Slicers:** Interactive filtering by Group and Territory to allow users to drill down into specific data segments.

## 🚀 How to Use This Repository
1. Clone the repository to your local machine.
2. Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
3. Open the `dashbord.pbix` file to interact with the dashboard.
4. Use the slicers on the right panel to filter data by specific territories or groups.

---
*Developed by Ahmed Abdelfattah*
