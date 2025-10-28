# 📦 Vendor Performance & Inventory Analysis | SQL · Python · Power BI  

Analyzing vendor efficiency and profitability to support strategic purchasing and inventory decisions using **SQL**, **Python**, and **Power BI**.

---

## 📌 Table of Contents  
- [Overview](#overview)  
- [Business Problem](#business-problem)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Data Preparation & Analysis](#data-preparation--analysis)  
- [Key Insights & Findings](#key-insights--findings)  
- [Dashboard](#dashboard)  
- [Final Recommendations](#final-recommendations)  
- [Author & Contact](#author--contact)  

---

## 🧭 Overview  
This project evaluates **vendor performance and retail inventory dynamics** to drive strategic insights for purchasing, pricing, and inventory optimization.  

A complete data pipeline was built using:  
- **SQL** for data extraction, cleaning, and transformation  
- **Python** for analysis and statistical validation  
- **Power BI** for interactive dashboards and storytelling  

---

## 🎯 Business Problem  
Efficient vendor and inventory management are crucial for retail success.  
This project aims to:  
- Identify underperforming vendors or brands needing pricing or promotional adjustments  
- Assess vendor contributions to overall sales and profits  
- Analyze bulk purchasing cost-benefits  
- Detect inventory turnover inefficiencies  
- Statistically compare vendor-level profitability  

---

## 🧾 Dataset  
- Multiple CSV files (`/data/` folder) covering **sales**, **vendors**, and **inventory**  
- Combined and transformed into vendor-level summary tables for analysis  
- Approximate size: *~30K–40K records, 20+ attributes*  

---

## 🛠 Tools & Technologies  
- **SQL** → Joins, Filtering, CTEs for data transformation  
- **Python** → *Pandas, Matplotlib, Seaborn, SciPy* for analysis and validation  
- **Power BI** → Interactive dashboard visualization  
- **GitHub** → Version control and project hosting  

---

## 🔍 Data Preparation & Analysis  
Key cleaning and transformation steps:  
- Removed invalid records (Gross Profit ≤ 0, Profit Margin ≤ 0, Sales Quantity = 0)  
- Created vendor-level summary tables and lookup merges  
- Detected and handled outliers (high freight costs, large purchase amounts)  
- Performed correlation and distribution analysis for deeper insights  

---

## 📊 Key Insights & Findings  
**Data Quality Observations**  
- Loss-making transactions found (Gross Profit: min −52,002.78)  
- Unsold inventory → slow-moving stock alerts  

**Outliers**  
- High freight costs (up to ₹2.57L)  
- Large deviations in purchase prices  

**Correlations**  
- Purchase Qty ↔ Sales Qty → **Strong Positive (0.999)**  
- Profit Margin ↔ Sales Price → **Weak Negative (−0.179)**  

**Business Insights**  
- 🔹 *198 brands* with low sales but high margins — ideal for promotions  
- 🔹 *Top 10 vendors* = **65.69%** of all purchases → over-reliance risk  
- 🔹 *72% cost savings* per unit in bulk purchases  
- 🔹 *$2.71M* worth of unsold inventory identified  
- 🔹 Profitability difference between high vs. low-performing vendors is **statistically significant**  

---

## 📈 Dashboard  
**Power BI Dashboard Highlights:**  
- Vendor-wise Sales & Profitability  
- Inventory Turnover and Bulk Purchase Analysis  
- Profit Margin Trends  
- Vendor Performance Heatmaps  

📊 **Dashboard File:**  
[`vendor_performance_dashboard.pbix`](./dashboard/vendor_performance_dashboard.pbix)  

---

## 💡 Final Recommendations  
✅ Diversify vendor base to mitigate over-reliance  
✅ Optimize bulk order sizes for cost efficiency  
✅ Reprice or promote slow-moving high-margin products  
✅ Clear stagnant inventory strategically  
✅ Strengthen vendor relationship programs based on performance metrics  

---

## 👤 Author & Contact  
**Sanskar Tripathi**  
_Data Analysis | SQL · Python · Power BI · Machine Learning_  


Email: [sanskar.trip.ai@gmail.com](mailto:sanskar.trip.ai@gmail.com)  
GitHub: [https://github.com/Sanskar-Trip-AI](https://github.com/Sanskar-Trip-AI)  
LinkedIn: [linkedin.com/in/sanskartripathi](https://www.linkedin.com/in/sanskartripathi)

---

