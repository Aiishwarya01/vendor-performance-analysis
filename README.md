# 🧾 Vendor Performance Analysis – Retail Inventory & Sales

Analyzing vendor efficiency and profitability to support strategic purchasing and inventory decisions using SQL, Python, and Power BI.

---
## Overview

This project evaluates vendor performance and retail inventory dynamics to drive strategic insights for purchasing, pricing, and inventory optimization. A complete data pipeline was built using SQL for ETL, Python for analysis and hypothesis testing, and Power BI for visualization.

---
## Business Problems

Effective inventory and sales management are critical in the retail sector. This project aims to:
- Identify underperforming brands needing pricing or promotional adjustments
- Determine vendor contributions to sales and profits
- Analyze the cost-benefit of bulk purchasing
- Investigate inventory turnover inefficiencies
- Statistically validate differences in vendor profitability

---
## What I Did

- Cleaned and explored vendor data using **Pandas** 
- Visualized insights using **Seaborn** and **Matplotlib**
- Wrote SQL queries to dig deeper into vendor performance
- Performed **hypothesis testing** to check if differences in vendor profitability are statistically significant
- Built a final **Power BI dashboard** to present key findings clearly

---
## Dashboard

- Power BI Dashboard shows:
  - Vendor-wise Sales and Margins
  - Inventory Turnover
  - Bulk Purchase Savings
  - Performance Heatmaps

---
## Tools & Technologies Used

- Python (Pandas, Scipy, Seaborn, Matplotlib)
- SQL 
- Power BI (Interactive Visualizations)

---
## Project Structure
```
vendor-performance-analysis/
│
├── README.md
│
├── notebooks/                  # Jupyter notebooks
│   ├── EDA.ipynb
│   ├── Vendor Performance Analysis.ipynb
│
├── scripts/                    # Python scripts for ingestion and processing
│   ├── ingestion_db1.py
│   └── get_vendor_summary.py
│
├── dashboard/                  # Power BI dashboard file
│   └── vendor_performance(1).pbix
│
├── images/                  
│   └── Dashboard.png
```

---
## How to Run This

1. Clone this repository:
```
git clone https://github.com/Aiishwarya01/vendor-performance-analysis.git
```

2. Load the CSVs and ingest into database:
```
python scripts/ingestion_db1.py
```

3. Create vendor summary table:
```
python scripts/get_vendor_summary.py
```

4. Open and run notebooks:
  - `notebooks/EDA.ipynb`
  - `notebooks/Vendor Performance Analysis.ipynb`

5. Open Power BI Dashboard:
  - `dashboard/vendor_performance(1).pbix`

---
## Contact

 📧 aishwaryasr097@gmail.com
 
 🔗 [LinkedIn](https://www.linkedin.com/in/aishwarya-sr/)
 
 🔗 [GitHub](https://github.com/Aiishwarya01)
