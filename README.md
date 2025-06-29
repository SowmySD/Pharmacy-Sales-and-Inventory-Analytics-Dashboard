# 💊 Pharmacy Sales and Inventory Analytics Dashboard


## Overview

Pharmacies often face challenges in managing inventory, forecasting demand, and minimizing expiry-related losses. In this project, we apply **data analytics and predictive modeling** to optimize operations at **Tamilnadu Co-operative Pharmacy**, helping improve efficiency and reduce wastage.

We collected real-time transaction data, performed detailed exploratory analysis, implemented forecasting models, and built an interactive Power BI dashboard to support data-driven decision-making.

---

## Business Context

- **Business Name**: Tamilnadu Co-operative Pharmacy  
- **Location**: East Veli Street, Madurai  
- **Objective**: Enable smarter inventory control, demand prediction, and expiry reduction through data-driven insights.

---

## Tech Stack

- Python (`pandas`, `pdfplumber`, `PyPDF2`, `scikit-learn`, `statsmodels`)
- Power BI
- Google Colab
- Google Sheets

---

## Data Collection

- Source: Official portal of [Tamil Nadu Co-operative Medical Stores](https://tncoopws.tn.gov.in/medicaljpc/usermanager/youLogin.jsp)
- Format: PDF invoices of transactions
- Tools: `PyPDF2`, `pdfplumber` used for PDF text extraction  
- Sample data spans from **October 2024 to February 2025**

---

## Data Preprocessing

- ✅ Removed noisy characters and standardized formats
- ✅ Converted data types (dates, prices, quantities)
- ✅ Removed duplicates and validated accuracy
- ✅ Final dataset ready for statistical modeling and visualization

---

## Analytics Performed

###  Statistical & Mathematical Models

- **Doctor-wise Prescription Analysis** — Identify commonly prescribed medicines per doctor
- **Bill Amount Distribution (Hypothesis Testing)** — Detect billing anomalies
- **Pareto Analysis (80/20 Rule)** — Identify top customers contributing to sales
- **Quantity vs Discount Correlation** — Discover influence of pricing on bulk buying
- **Cohort Analysis** — Understand patient retention and repeat behavior
- **Product Life Cycle Curve** — Track sales stages (intro, growth, maturity, decline)
