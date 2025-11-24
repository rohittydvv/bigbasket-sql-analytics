# 🛒 BigBasket Quick Commerce Data Analytics Using SQL

## 📝 Description

End-to-end SQL analytics project using BigBasket quick commerce transactional data. This repository demonstrates advanced SQL skills across data engineering, modeling, cleansing, analysis, and insight generation.

## 🏗️ Data Architecture

(diagrams/data_architecture.png)

**Bronze Layer:** Raw CSV data ingestion, all fields as-is for traceability.  
**Silver Layer:** Cleansed, standardized tables with derived columns and validated business logic.  
**Gold Layer:** Star schema views and aggregated tables for high-performance analytical querying.

---

## 🔍 Project Overview

This project analyzes real-world BigBasket quick-commerce data using SQL Server, building a retail-grade data warehouse and uncovering actionable business insights through structured, maintainable SQL workflows.

### 🎯 Goals

- Create a robust star schema warehouse for quick commerce analytics
- Transform, validate, and enrich raw operational data for accuracy and usability
- Build modular SQL queries and views for exploratory and advanced analytics
- Extract meaningful KPIs for business decision support

---

## 🧩 Entity Relationship (ER) Diagram

(diagrams/ER_diagram.png)

---

## 📁 Repository Structure

```text
├── dataset/                            # Raw BigBasket datasets (CSV)  
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for initial data ingestion
│   ├── silver/                         # Scripts for cleaning/transforming data
│   ├── gold/                           # Scripts for star schema and aggregates
│
├── tests/                              # Test scripts for Silver Layer
│
├── eda_queries/                        # Exploratory analytics scripts
│                        
├── advanced_analytics/                 # Deep business insights scripts
│
├── diagrams/                           # Data architecture and ER diagrams
└── README.md
```
## 🚀 Project Highlights

- Retail-optimized star schema with fact and dimension modeling  
- Automated cleansing and enrichment pipeline using stored procedures  
- Modular, reusable SQL transformations designed for scalability  
- Robust data quality checks (nulls, duplicates, relationship integrity)  
- In-depth exploratory and advanced analysis modules  

---

## 📊 Exploratory Data Analysis (EDA) – Key Findings

- Analyzed monthly trends in customer registrations, order volume, and total revenue
- Evaluated Average Order Value (AOV) patterns to understand customer spending behavior
- Studied the relationship between marketing spend and revenue over time
- Performed RFM and tenure-based segmentation to profile different customer groups
- Identified top customers and top products based on revenue and frequency metrics
- Assessed delivery efficiency and service quality using delay metrics and customer ratings
- Conducted cohort and cumulative analysis to understand retention and long-term growth patterns

---

## 🧪 Advanced Analysis – Key Insights

- Measured MoM and YoY revenue growth to evaluate short- and long-term business momentum
- Identified peak ordering periods by hour and weekday for demand timing analysis
- Compared weekday vs weekend purchasing behavior for operational planning
- Isolated high-demand, high-margin products to support profitability strategies
- Analyzed channel and campaign performance to evaluate marketing effectiveness and ROI
- Investigated the impact of delivery delays on customer sentiment and ratings
- Calculated and compared Customer Lifetime Value (CLV) across tenure segments and payment methods

---

## ⚠️ Important Notes / Warnings

- All scripts tested using SQL Server Express; syntax may require adaptation for other platforms
- Always run ingestion, cleaning, and transformation scripts in **bronze → silver → gold** order

---

## 📫 Contact

For questions, collaboration, or portfolio feedback:

**Email:** rohit.ydvv23@gmail.com  
**LinkedIn:** linkedin.com/in/rohittydvv

---

Thank you for reviewing this project.

Built to demonstrate excellence in SQL analytics, retail business modeling, and actionable data-driven storytelling.
