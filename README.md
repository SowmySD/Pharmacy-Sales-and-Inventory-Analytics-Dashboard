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

## 📈 Statistical & Mathematical Models in Pharma Analytics

- Analyze **doctor-wise prescriptions** to identify frequently prescribed medicines per doctor.
- Use **bill amount distribution with hypothesis testing** to detect anomalies in billing.
- Apply **Pareto analysis (80/20 rule)** to find top customers contributing to majority of sales.
- Study **quantity vs discount correlation** to evaluate the impact of pricing on bulk purchases.
- Perform **cohort analysis** to understand patient retention and repeat purchase behavior.
- Map **product life cycle curves** to track sales through introduction, growth, maturity, and decline.
- Utilize **descriptive statistics** to summarize average demand, variability, and peak periods.
- Conduct **trend analysis** to identify rising or falling patterns in medicine popularity.
- Implement **correlation analysis** to explore relationships between demographics, diseases, and drug usage.
- Leverage **time series analysis** to forecast seasonal and temporal demand for tablets.


## 🔮 Prediction Models Used

Advanced **machine learning** and **mathematical models** are highlighted to forecast demand and optimize stock levels:

- **Linear Regression**: Predicting demand based on historical consumption data.
- **ARIMA Model**: Time series-based approach to model seasonal trends in tablet consumption.
- **Decision Trees**: For classifying types of medicines by usage and availability.
- **K-Means Clustering**: Segmenting patient groups or drug types for targeted inventory planning.

These models are essential in enabling **proactive decision-making** rather than reactive stock management.

---

## 💡 Key Insights

- 📦 **Inventory Optimization**: Reduced overstock and out-of-stock situations using data-driven predictions.
- 🏥 **Healthcare Efficiency**: Enhanced ability to meet patient needs with accurate forecasting.
- 🔁 **Data Feedback Loops**: Real-time updates to prediction models as more data is collected.

---

## 🌐 Role of Data Science in Pharma

- 📉 Reducing drug wastage through accurate demand forecasting
- 🚑 Supporting public health planning and hospital readiness
- 🧾 Assisting pharmacists with dashboard-based monitoring systems
- 🔄 Integrating with IoT and EHR (Electronic Health Records) for real-time tracking

---

## 📊 Visualizations & Dashboards

The blog discusses how **interactive dashboards** are built to present:
- Daily tablet sales trends
- Stock depletion rates
- Disease vs medicine correlation graphs
- Predictive alerts for low inventory levels

These visual tools help stakeholders—from pharmacists to data scientists—make timely and informed decisions.

---

## 🧾 Real-Life Application Example

> Tamil Nadu Co-operative Pharmacy used analytics to forecast the demand of common fever tablets during a seasonal outbreak, leading to better preparedness and zero wastage.

---
