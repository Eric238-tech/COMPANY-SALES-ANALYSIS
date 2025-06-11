📦 Company Sales Analysis

A small but powerful Power BI dashboard with key insights.

This project presents an interactive and data-rich **Sales Performance Dashboard** built in **Power BI**. It provides comprehensive insights into company-wide sales operations, allowing users to explore revenue trends, profitability, and product movement across various markets and segments.

---

### 📊 Dashboard Overview

The dashboard is designed to help users:

* Analyze **Total Sales**, **Total Profit**, and **Order Quantity** across time and geography
* Track **average profit per product** to understand margin efficiency
* Explore sales performance by **Product Category**, **Manufacturer**, and **Sales Channel**
* Understand **regional demand** through Order Quantity by Region
* Visualize **country-level performance** on an interactive sales map
* Use **dynamic slicers** to filter data by:

  * **Month**
  * **Manufacturer**
  * **Product Category**
  * **Sales Channel**
  * **Country**

This flexibility supports data-driven decision-making across departments including sales, marketing, and supply chain.

---

### 🧮 Key DAX Measures Used

```DAX
Total Sales = SUM(Sales[Sales Amount])
Total Profit = SUM(Sales[Profit])
Total Orders = SUM(Sales[Order Quantity])
Avg Profit per Product = DIVIDE([Total Profit], DISTINCTCOUNT(Sales[Product Name]))
```

Additional visual-level calculations include sales share by category, manufacturer rankings, and regional comparisons.

---

### 🛠️ Tools & Technologies

* **Power BI**: Dashboard development, data modeling, slicer interactivity
* **DAX**: Measure calculations and performance metrics
* **Power Query**: Data transformation and cleansing
* **Visuals Used**:

  * **Bar & Column Charts** (e.g., Sales by Category, Manufacturer, Promotion)
  * **Map Visual** (Geographic Sales Distribution)
  * **Cards** (KPI display)
  * **Pie Chart** (Product segmentation)
  * **Line Chart** (Trend analysis)

---

### 📂 Files Provided

* `Company_Sales_Analysis.pbix` – Power BI report file
* `Sales_Data.xlsx` – Raw dataset (for practice or extension)
* `Dashboard_Screenshots/` – Folder with preview images

---

### 🚀 How to Use

1. Download the repository
2. Open the `.pbix` file using Power BI Desktop
3. Use the slicers and charts to explore different sales dimensions and gain insights



### 📸 Dashboard Preview


Happy Analyzing! 📈


**#PowerBI #SalesDashboard #DataAnalytics #DAX #BusinessIntelligence #DataVisualization**

