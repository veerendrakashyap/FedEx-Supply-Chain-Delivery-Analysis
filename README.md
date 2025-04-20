# FedEx Supply Chain Delivery Analysis 🚚📦

### 🔍 Project Type: Exploratory Data Analysis (EDA) | Regression | Classification | Unsupervised Learning  

---

## 📌 Project Summary

The **FedEx Supply Chain Delivery Analysis** project is an in-depth analytical study using real-world logistics data from FedEx. With over **10,000 shipment records**, this project explores delivery performance, shipment costs, vendor efficiency, and late delivery patterns across countries and shipping modes.

Using Python, Pandas, Seaborn, and Matplotlib, the project identifies operational inefficiencies and delivers actionable business insights to enhance FedEx's global delivery reliability.

---

## 🧠 Problem Statement

FedEx seeks to improve its shipping reliability and reduce delays. The primary objective of this project is to **identify the root causes of late deliveries** and recommend data-driven strategies for optimization.

---

## 🎯 Business Objectives

- Identify shipment modes contributing most to late deliveries.
- Understand which vendors and countries are frequently involved in delays.
- Analyze the correlation between cost, weight, shipment type, and delivery performance.
- Provide actionable recommendations to reduce operational bottlenecks and improve customer satisfaction.

---

## 📂 Dataset Overview

- **Rows:** 10,324
- **Columns:** 33
- **Key Features:**
  - Country
  - Vendor
  - Shipment Mode (Air, Truck, Ocean)
  - INCO Terms
  - Delivery & Scheduled Dates
  - Freight Cost, Line Item Value, Insurance
  - Delivery Duration (Engineered)
  - Late Delivery Flag (Engineered)

---

## 🛠️ Key Tasks Performed

- ✅ Data Cleaning & Null Value Treatment  
- ✅ Feature Engineering: `Delivery_Duration` and `Late_Delivery_Flag`  
- ✅ Statistical Summary & Unique Value Checks  
- ✅ Correlation Analysis  
- ✅ Advanced Data Visualizations  
- ✅ Root Cause Identification for Late Deliveries  
- ✅ Actionable Business Recommendations  

---

## 📊 Visualizations Included

| Chart Type        | Description |
|-------------------|-------------|
| Bar Chart         | Top 10 Countries by Deliveries |
| Count Plot        | Shipment Mode Distribution |
| Horizontal Bar    | Top Vendors by Shipments |
| Count Plot        | INCO Term Distribution |
| Bar Plot          | Late Deliveries by Shipment Mode |
| Histogram + KDE   | Freight Cost Distribution |
| Histogram + KDE   | Delivery Duration Distribution |
| Box Plot          | Line Item Value by Country |
| Scatter Plot      | Line Item Quantity vs Freight Cost |
| Bar Chart         | Top Countries with Late Deliveries |
| Grouped Countplot | Shipment Mode Usage in Top 5 Countries |
| Horizontal Bar    | Vendors with Most Late Deliveries |
| Bar Plot          | Avg. Delivery Duration by Shipment Mode |
| Heatmap           | Correlation Between Numeric Features |
| Pairplot          | Key Numeric Metric Interactions |
| Box Plot          | Freight Cost by Shipment Mode |
| Scatter Plot      | Weight vs Freight Cost (Late Delivery Colored) |
| Count Plot        | Deliveries by Year |
| Bar Chart         | Avg. Line Item Value by Vendor |
| Grouped Bar       | Shipment Mode by INCO Term |

---

## 💡 Key Insights

- **Air** shipment is the most common but shows **high variance in delay rates**.
- **Certain countries** and **vendors** consistently report late deliveries.
- **Heavier shipments** incur higher freight but aren’t always delayed.
- Specific **INCO terms** align with specific shipment modes.
- High freight costs **do not always guarantee timely delivery**.

---

## ✅ Recommendations

1. **Reassess shipment mode** usage — switch to more reliable ones when necessary.
2. **Build a delay prediction model** using historical patterns.
3. **Monitor vendor performance** using scoring systems.
4. **Optimize INCO terms** based on cost-responsibility balance.
5. **Use Power BI/Tableau dashboards** for real-time monitoring.
6. **Improve data capture & quality control** to support analytics-driven decisions.
