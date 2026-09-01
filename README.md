# Microsoft Fabric End-to-End Analytics Portfolio 🚀

Welcome to my comprehensive Microsoft Fabric portfolio! This repository showcases a complete, end-to-end data analytics and business intelligence solution built across various Microsoft Fabric workloads, moving from raw data ingestion to advanced semantic modeling and executive reporting.

---

## 🏗️ Repository Structure & Labs

| Module / Folder | Description & Key Components | Status |
| :--- | :--- | :--- |
| **`01_LakehouseLab`** | Ingesting raw data into OneLake, unifying storage, and structuring files for downstream analytics. | Completed ✅ |
| **`02_WarehouseLab`** | Enterprise data warehousing, table optimization, and relational schema management. | Completed ✅ |
| **`03_SQLDatabaseLab`** | Transactional querying, T-SQL scripts, views, and data validation. | Completed ✅ |
| **`04_DataScienceLab`** | Exploratory data analysis, Python notebooks, and machine learning workflows. | Completed ✅ |
| **`05_RealTimeLab`** | Streaming data processing and KQL (Kusto Query Language) querying for real-time insights. | Completed ✅ |
| **`06_SalesSemanticModel`** | Star schema data modeling, advanced DAX measures (`Total Sales`, `Sales YTD`), and Power BI dashboards. | Completed ✅ |

---

## 🌟 Key Highlights & Highlights from Modules

### 1. Sales Semantic Model & Business Intelligence (`06_SalesSemanticModel`)
* **Star Schema Architecture:** Designed optimized 1-to-many relationships connecting a central fact table (`fact_sale_order`) with clean dimension tables (`dim_customer`, `dim_product`, `dim_date`).
* **Advanced DAX Calculations:**
  - *Total Sales:* `Total Sales = SUM(fact_sale_order[SalesAmount])`
  - *Sales Year-to-Date:* `Sales YTD = TOTALYTD([Total Sales], dim_date[FullDateAlternateKey])`
* **Power BI Reports:** Developed interactive visualizations including *Total Sales by Country Region*.

---

## 🛠️ Tech Stack & Skills
* **Platform:** Microsoft Fabric (OneLake, Lakehouse, Warehouse, SQL Database, Real-Time Analytics)
* **Languages & Querying:** T-SQL, DAX, KQL, Python
* **Data Modeling:** Dimensional Modeling (Star Schema)
* **Visualization:** Power BI

---
