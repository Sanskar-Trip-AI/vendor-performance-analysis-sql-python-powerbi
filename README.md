# 📦 Vendor Performance & Inventory Analysis | SQL · Python · Power BI  

Vendor Performance Analysis focuses on evaluating supplier efficiency across metrics like sales, profit, delivery reliability, and inventory impact.  
The goal is to identify top-performing vendors, cost-saving opportunities, and inefficiencies in inventory and procurement.

---

## 📘 Table of Contents
- [Overview](#-vendor-performance-analysis)
- [Business Problem](#-business-problem)
- [Dataset](#️-dataset)
- [Tools & Technologies](#-tools--technologies)
- [Project Structure](#-project-structure)
- [Data Preparation](#-data-preparation)
- [Key Insights & Findings](#-key-insights--findings)
- [Dashboard](#-dashboard)
- [Final Recommendations](#-final-recommendations)
- [Author & Contact](#-author--contact)

---

## 🧩 Business Problem

Companies often suffer losses due to inefficient vendor management, high freight costs, or poor inventory turnover.  
This project addresses:

- Identifying underperforming vendors for corrective actions  
- Analyzing top contributors to sales and profit  
- Understanding the effect of bulk orders on cost savings  
- Detecting slow-moving or unsold inventory  
- Assessing dependency risks on key vendors  

---

## 🗂️ Dataset

**Data Source:** `inventory.db` (SQLite database)  
Contains tables for purchases, sales, freight, and vendor details.

Approx. **25K+ records**, covering:
- Vendor information  
- Sales & purchase transactions  
- Freight and excise data  
- Pricing and volume metrics  

📁 **Access Data:** [Google Drive Link](https://drive.google.com/file/d/1OycGXzQfY5aKn1kbR07l_Qw7pQ_hlrkp/view?usp=sharing)

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Python** | Data analysis & scripting |
| **Pandas** | Data manipulation |
| **SQL** | Data extraction & aggregation |
| **Power BI** | Dashboard visualization |
| **Matplotlib / Seaborn** | Exploratory data visualization |
| **Jupyter Notebook** | Data exploration and analysis |

---

## 🧱 Project Structure
Vendor_Performance_Analysis/
│
├── data/
│ └── inventory.db
├── sql/
│ └── final_query.sql
├── notebooks/
│ └── Vendor_Performance_Analysis.ipynb
├── powerbi/
│ └── vendor_performance_dashboard.pbix
├── report/
│ └── final_report.pdf
└── README.md

---

## 🔍 Data Preparation

- Connected to SQLite database via **SQLAlchemy**  
- Cleaned missing values and removed zero/negative profit entries  
- Merged purchase, sales, and freight data using **SQL CTEs**  
- Aggregated brand- and vendor-level performance metrics  

---

## 📊 Key Insights & Findings

### Data Highlights
- Negative/zero profit entries identified and excluded  
- Unsold inventory → slow-moving SKUs detected  
- High freight outliers up to ₹2.57L  

### Correlation
- Purchase Qty ↔ Sales Qty → **Strong (0.999)**  
- Profit Margin ↔ Sales Price → **Weak Negative (−0.179)**  

### Business Insights
- 🔹 198 brands with low sales but high margins → target for promotions  
- 🔹 Top 10 vendors account for **65.7%** of purchases → dependency risk  
- 🔹 **72% unit cost savings** via bulk purchasing  
- 🔹 **$2.71M unsold stock** → inventory lockup  
- 🔹 Significant margin gap between top and bottom vendors  

---

## 📈 Dashboard

### Power BI Dashboard Features
- Vendor-wise Sales, Profit, and Margin metrics  
- Inventory Turnover & Bulk Purchase analysis  
- Profit Margin Heatmaps & KPI Cards  
- Vendor Comparison & Trend Analysis  

📁 **File:** `powerbi/vendor_performance_dashboard.pbix`  
📸 *(Add dashboard preview image here once uploaded)*

---

## 💡 Final Recommendations

✅ Diversify vendor base to reduce over-reliance  
✅ Optimize bulk orders for cost efficiency  
✅ Promote slow-moving, high-margin products  
✅ Implement vendor scorecards for continuous monitoring  
✅ Leverage data insights for better contract negotiations  


---

## 👤 Author & Contact  
**Sanskar Tripathi**  
_Data Analysis | SQL · Python · Power BI · Machine Learning_  


Email: [sanskar.trip.ai@gmail.com](mailto:sanskar.trip.ai@gmail.com)  
GitHub: [https://github.com/Sanskar-Trip-AI](https://github.com/Sanskar-Trip-AI)  
LinkedIn: [linkedin.com/in/sanskartripathi](https://www.linkedin.com/in/sanskartripathi)

---

