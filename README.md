# Supply Chain Analytics Dashboard (Power BI)

This project is an interactive Supply Chain Analytics Dashboard built using Python (Jupyter Notebook) for data preparation and Power BI for visualization.

It analyzes delivery performance, delay causes, vendor reliability, and financial impact to support data-driven business decisions.

### 📊 Project Overview

The dashboard provides a structured view of supply chain operations including:

Total Orders

On-Time Delivery %

Delayed Orders

Average Delay Days

Cost of Delay

Vendor Risk Analysis

It helps identify:

High-risk vendors

Major delay drivers

Cost concentration areas

### Files Provided

1) supply_chain_data.csv
2) supply_chain_data_clean.csv
3) Supply Chain Data Preprocessing.ipynb
4) Supply Chain Dashboard.pbix

### 🚀 Key Features

📌 Executive KPI summary (Total Orders, On-Time %, Shipment Cost etc.)

📌 Delay Root Cause Analysis by reason, product category, and city

📌 Vendor Risk Quadrant (Avg Delay Days vs Vendor Rating)

📌 Vendor Risk Heatmap by delay reason

📌 Pareto analysis of Delay Cost by Vendor

📌 Interactive slicers for Month, Delay Reason, Product Category, and City

📌 Dedicated Recommendations page based on insights

### 🗂 Dataset Information

The dataset simulates supply chain operations across:

Multiple vendors

Product categories

Cities

Monthly time periods

### Key Fields:

| Column Name                | Description                         |
| -------------------------- | ----------------------------------- |
| **Order ID**               | Unique identifier for each shipment |
| **Product Category**       | Type of product shipped             |
| **Vendor Display Name**    | Logistics vendor name               |
| **Order Date**             | Order creation date                 |
| **Expected Delivery Date** | Planned delivery date               |
| **Actual Delivery Date**   | Actual delivery date                |
| **Delivery Status**        | On-Time / Delayed                   |
| **Delay Reason**           | Cause of delay                      |
| **Vendor Rating**          | Vendor performance rating           |
| **Shipment Cost**          | Cost of shipment                    |
| **Delay Days**             | Calculated delivery delay           |

### 🛠 Tools Used

Python (Jupyter Notebook) – Data cleaning & preprocessing

Pandas & NumPy – Data transformation

Power BI – Data modeling & interactive dashboard

DAX – KPI calculations & vendor risk scoring

### ▶️ How to Use

Open the .pbip / .pbix file in Power BI Desktop.

Navigate through dashboard pages:

Overview

Delay Analysis

Vendor Scoring

Recommendations

Use slicers (Month, Delay Reason, Product Category, City) to filter data.

Interact with visuals to explore delay trends and vendor risk.

### 📈 Dashboard Pages
🔹 Page 1 – Overview

Executive KPI cards

Monthly order trend

On-Time vs Delayed split

Product category distribution


🔹 Page 2 – Delay Root Cause Analysis

Avg Delay by reason

Cost impact by product category

City-level delay cost map


🔹 Page 3 – Vendor Reliability & Risk Analysis

Vendor Risk Quadrant

Vendor Risk Heatmap

Pareto chart of Delay Cost

Vendor ranking table



🔹 Page 4 – Recommendations

High & medium priority actions

Vendor accountability strategy

Cost reduction insights



### Dashboard Snippet

<img width="1119" height="631" alt="image" src="https://github.com/user-attachments/assets/d6464cc8-cd84-4faf-93b9-a63d94a17ee2" />


### 💡 Key Insights

Delay duration is the strongest risk driver.

A small group of vendors contributes disproportionately to delay cost.

Vendor, operational, and traffic issues are primary delay causes.

Geographic patterns influence delay performance.

### 🎯 Business Impact

This dashboard helps businesses:

- Reduce delivery delays

- Optimize vendor selection

- Control logistics costs

- Improve strategic decision-making
