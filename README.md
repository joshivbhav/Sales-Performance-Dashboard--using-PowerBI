# Sales-Performance-Dashboard--using-PowerBI
# 📊 Vaibhav Ecommerce Sales Dashboard
 
**An interactive Power BI business intelligence solution for end-to-end sales performance analysis.**
 
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/status-active-success?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
 
---
 
## 📌 Overview
 
The **Vaibhav Ecommerce Sales Dashboard** is a self-contained Power BI report built to transform raw transactional order data into a single, decision-ready view of business performance. It consolidates revenue, profitability, order volume, and customer behavior into one interactive canvas — enabling stakeholders to move from *"what happened"* to *"what to do next"* without touching a spreadsheet.
 
This project demonstrates a practical, production-style application of data modeling, DAX, and dashboard design principles commonly used in retail and e-commerce analytics.
 <img width="1920" height="1080" alt="17-50-59 (2)" src="https://github.com/user-attachments/assets/4637d346-9eff-48bd-9782-d6204fa84e04" />

---
 
## 🎯 Business Objective
 
E-commerce operations generate high-volume transactional data across categories, regions, and payment channels, but that data is only valuable if it's accessible and interpretable. This dashboard was built to:
 
- Centralize sales, profit, and order data into a governed, single source of truth
- Surface performance trends by **category**, **sub-category**, **state**, and **payment mode**
- Track core commercial KPIs at a glance for fast, confident decision-making
- Replace static, manual reporting with a live, filterable analytical tool
---
 <img width="1339" height="755" alt="Screenshot 2026-07-18 172107" src="https://github.com/user-attachments/assets/8b785b71-adee-44bc-b46d-95f5a8aba5d0" />

## ⚙️ Key Features
 
| Feature | Description |
|---|---|
| 📈 **KPI Summary Cards** | At-a-glance headline metrics for revenue, profit, and order performance |
| 🥯 **Category & Sub-Category Breakdown** | Bar and column charts revealing top- and bottom-performing product segments |
| 🍩 **Payment Mode Distribution** | Donut chart visualizing customer payment preferences |
| 🗺️ **State-Level Performance** | Geographic breakdown of sales concentration |
| 🎚️ **Interactive Slicers** | Dynamic filtering by date, category, and customer attributes for on-demand analysis |
| 🎨 **Custom Dark Theme** | A polished, presentation-ready visual theme tailored for executive reporting |
 
---
 
## 🧮 Data Model
 
The report is built on a structured data model with the following core fields:
 
- `Order Date`
- `Category` / `Sub-Category`
- `Customer Name` / `State`
- `Payment Mode`
- `Quantity`
- `Amount` / `Profit`
- `AOV` (Average Order Value) — calculated measure
Measures such as **AOV** are derived using DAX to provide analysis-ready metrics without requiring manual computation downstream.
 
---
 
## 🛠️ Tech Stack
 
- **Power BI Desktop** — report authoring & data modeling
- **Power Query (M)** — data cleaning and transformation
- **DAX** — calculated measures and KPIs
- **Star-schema-oriented data modeling** principles for query performance
---
 
## 🚀 How to Use
 
1. Clone or download this repository
2. Open `Sales-Performance-Dashboard.pbix` in **Power BI Desktop** (2023 or later recommended)
3. Use the slicers on the report canvas to filter by date, category, or customer segment
4. Hover over visuals for detailed tooltips; click any data point to cross-filter the entire report
> 💡 No external data connections are required — the dataset is embedded within the `.pbix` file for full portability.
 
---
 
## 📂 Repository Structure
 
```
├── Sales-Performance-Dashboard.pbix   # Power BI report file
└── README.md                          # Project documentation
```
 
---
 
## 🔍 Why This Project Matters
 
Dashboards like this reflect a core discipline in modern analytics: converting raw operational data into a governed, self-service reporting layer that reduces reliance on manual analysis and accelerates decision-making. It showcases practical proficiency in **data modeling, DAX, UX-focused report design, and business-oriented KPI framing** — skills directly transferable to real-world BI and data analyst roles.
 
---
 
## 👤 Author
 
**Vaibhav** **Joshi**


---
 
## 📄 License
 
This project is released under the [MIT License](LICENSE) — free to use, modify, and distribute with attribution.
