# 📊 Insurance Analysis Dashboard

This repository contains an end-to-end **Insurance Portfolio Analysis Dashboard** built using **AWS S3, Snowflake, SQL, and Power BI**. The project demonstrates a modern cloud-based analytics pipeline that transforms raw insurance data into meaningful business insights through data engineering, modeling, and interactive visualizations.

---

#  Project Overview

The primary objective of this project is to analyze insurance portfolio data to help stakeholders monitor business performance, understand customer demographics, evaluate claim trends, and make data-driven decisions.

The project follows a complete cloud analytics workflow:

* Data storage in **AWS S3**
* Data ingestion into **Snowflake**
* Data cleaning and transformation using **Snowflake SQL**
* Additional data preparation using **Power Query**
* Interactive dashboard development using **Power BI**
* Business insights generated using **DAX measures** and optimized data modeling

---

#  Key Features

## ☁️ Cloud Data Pipeline

* Raw insurance datasets stored in **AWS S3**.
* Secure data ingestion from AWS S3 into Snowflake.
* Scalable cloud data warehouse implementation using Snowflake.
* Centralized storage for structured insurance portfolio data.

---

##  ETL & Data Preparation

* Imported insurance data from AWS S3 into Snowflake.
* Cleaned and transformed datasets using Snowflake SQL.
* Removed duplicate records and handled missing values.
* Standardized data formats for accurate reporting.
* Performed additional transformations using Power Query.
* Built an optimized data model with relationships between multiple tables.

---

##  Insurance Portfolio Analysis

The dashboard enables users to analyze:

* Premium Collection Trends
* Total Claims and Claim Amounts
* Policy Distribution
* Customer Demographics
* Policy Coverage Analysis
* Premium vs Claims Comparison
* Regional Insurance Performance
* Customer Segmentation
* Business Growth Trends
* Key Insurance KPIs

---

##  Power BI Dashboard

The dashboard provides interactive visualizations including:

* KPI Cards
* Line Charts
* Clustered Bar Charts
* Stacked Column Charts
* Pie & Doughnut Charts
* Matrix Tables
* Interactive Filters and Slicers
* Drill-down Reports
* Cross-filtering Visualizations

---

##  Data Modeling & DAX

Implemented an optimized Power BI semantic model using:

* Star Schema Data Model
* Relationships between Fact and Dimension tables
* Custom DAX Measures
* Time Intelligence Functions
* Dynamic KPIs
* Percentage Calculations
* Business Performance Metrics
* Interactive Filtering

---

# ☁️ Cloud Architecture

```
Insurance Dataset
        │
        ▼
     AWS S3
        │
        ▼
   Snowflake Stage
        │
        ▼
Snowflake Data Warehouse
        │
   Snowflake SQL
        │
        ▼
   Power Query
        │
        ▼
    Power BI
        │
        ▼
Interactive Insurance Dashboard
```

---

#  Dashboard Insights

The dashboard helps answer important business questions such as:

* What is the total premium collected?
* Which policy types generate the highest revenue?
* Which regions contribute the highest premium income?
* How do claim amounts compare with premium collections?
* Which customer demographics purchase the most policies?
* Which insurance products have the highest claim frequency?
* How is the insurance portfolio performing over time?
* Which business areas require strategic improvement?

---

#  Tools & Technologies

| Tool          | Purpose                                     |
| ------------- | ------------------------------------------- |
| AWS S3        | Cloud storage for insurance datasets        |
| Snowflake     | Cloud data warehouse                        |
| Snowflake SQL | Data cleaning, transformation, and querying |
| Power Query   | Data transformation and preprocessing       |
| DAX           | Business logic and KPI calculations         |
| Power BI      | Dashboard development and visualization     |

---

#  End-to-End Workflow

1. Upload insurance datasets to AWS S3.
2. Load data into Snowflake using cloud storage integration.
3. Clean and transform data using Snowflake SQL.
4. Perform additional preprocessing using Power Query.
5. Build relationships and semantic data model in Power BI.
6. Create DAX measures for business KPIs.
7. Develop interactive dashboards and reports.
8. Generate actionable insights for insurance portfolio analysis.

---

#  Dashboard Highlights

* Cloud-based analytics pipeline using AWS and Snowflake.
* Scalable data warehouse architecture.
* Interactive Power BI dashboard with advanced visualizations.
* Optimized semantic data model for high-performance reporting.
* Dynamic DAX measures for real-time business analysis.
* End-to-end ETL pipeline from cloud storage to business intelligence.

---

<img width="1336" height="745" alt="Screenshot 2026-06-22 105757" src="https://github.com/user-attachments/assets/a355ec64-9c38-4059-872a-93f2da8df038" />


# 📌 How to View the Dashboard

1. Clone or download this repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Explore the dashboard using interactive filters, slicers, and drill-down reports.
4. Analyze insurance KPIs, premium collections, claims, customer demographics, and policy performance.

---

#  Project Outcome

This project demonstrates an end-to-end cloud business intelligence solution by integrating:

* AWS S3 for scalable cloud storage
* Snowflake for enterprise data warehousing
* Snowflake SQL for data transformation
* Power Query for ETL and preprocessing
* Power BI for interactive dashboard development
* DAX for advanced business calculations

The final dashboard enables insurance companies to monitor portfolio performance, evaluate claims, analyze customer behavior, and support strategic decision-making through interactive, cloud-powered analytics.
