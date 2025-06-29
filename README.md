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

##  Data Collection

- **Source**: Tamil Nadu Co-operative Medical Stores Portal  
  🔗 [Visit Portal](https://tncoopws.tn.gov.in/medicaljpc/usermanager/youLogin.jsp) 

- **Data Duration**: October 2024 – February 2025

- **Method**:  
  Bills were downloaded as **PDFs** and parsed using Python libraries like [`PyPDF2`](https://pypi.org/project/PyPDF2/)  and [`pdfplumber`](https://pypi.org/project/pdfplumber/)

- **Sample Data Fields**:
  - Bill Number, Date  
  - Doctor & Patient Name  
  - Medicine Name & Manufacturer  
  - Quantity, Expiry, Price, GST, Discount  
  - Total Payment

- 📄 [Sample Dataset Link](https://docs.google.com/spreadsheets/d/1qMRmSIWhoCjH6jh9y78FnBhAW_8NQ6W6/edit?gid=1724690391#gid=1724690391) 
---

## Data Preprocessing

- ✅ Removed noisy characters and standardized formats
- ✅ Converted data types (dates, prices, quantities)
- ✅ Removed duplicates and validated accuracy
- ✅ Final dataset ready for statistical modeling and visualization

---

## Analytics Performed

##  Statistical & Mathematical Models 

### 📊 Descriptive & Diagnostic
- **Descriptive Stats** – Avg. demand & variability.
- **Trend Analysis** – Track drug popularity over time.
- **Doctor-wise Analysis** – Most prescribed meds per doctor.
- **Product Life Cycle** – Sales stages: intro to decline.

### 🧪 Statistical Testing
- **Hypothesis Testing** – Detect billing anomalies.
- **Pareto Rule (80/20)** – Top customers driving sales.

### 🔄 Correlation & Behavior
- **Correlation Analysis** – Link between demographics & usage.
- **Discount Impact** – Effect of discounts on bulk buying.
- **Cohort Analysis** – Repeat patient behavior.

### ⏱️ Predictive Modeling
- **Time Series** – Forecast seasonal tablet demand.

---

##  Prediction Models Used

Advanced **machine learning** and **mathematical models** are highlighted to forecast demand and optimize stock levels:

- **Linear Regression**: Predicting demand based on historical consumption data.
- **ARIMA Model**: Time series-based approach to model seasonal trends in tablet consumption.
- **Decision Trees**: For classifying types of medicines by usage and availability.
- **K-Means Clustering**: Segmenting patient groups or drug types for targeted inventory planning.

These models are essential in enabling **proactive decision-making** rather than reactive stock management.

---

## Dashboard

All analysis and predictions are consolidated into a **Power BI Dashboard** offering:

- 🔍 Interactive filtering and exploration  
- 📈 Real-time sales trend monitoring  
- 🚨 Stock-level alerts  
- 🧑‍⚕️ Doctor-prescription tracking  
- 🔮 Predictive insights for planning  

🔗 [View Dashboard](https://app.powerbi.com/links/ReA0aFVzoV?ctid=562673cb-3a12-4428-9c2e-82d74fd5889a&pbi_source=linkShare) 

🎥 **Dashboard Walkthrough Video**  
🔗 [Watch Video](https://drive.google.com/file/d/1TzLw6Na8McX-zzxVVAEEG715MXMozhqj/view) 

![Alt Text]()
![Alt Text]()
![Alt Text]()
![Alt Text]()

---

##  Code & Tools

### 🛠️ Languages & Tools : Python , Power BI , Pandas , Matplotlib , Statsmodels , Scikit-learn  
### 📚 Libraries Used
- `PyPDF2`, `pdfplumber` – For PDF text extraction  
- `pandas`, `numpy` – Data manipulation and cleaning  
- `matplotlib`, `seaborn` – Data visualization  
- `statsmodels` – Time series forecasting (ARIMA, SARIMA)  
- `sklearn` – Machine learning (Random Forest Classification)  

🔗 [Google Colab Notebook](https://colab.research.google.com/drive/1Ae-iLvD8h7r4AR00UxYPUVCmZUiDxTYt?usp=sharing) 

---

##  Role of Data Science in Pharma

- 📉 Reducing drug wastage through accurate demand forecasting
- 🚑 Supporting public health planning and hospital readiness
- 🧾 Assisting pharmacists with dashboard-based monitoring systems
- 🔄 Integrating with IoT and EHR (Electronic Health Records) for real-time tracking

---

##  Outcome

This project successfully:

- ✅ Reduced medicine expiry waste through proactive classification  
- ✅ Improved stock management using forecasting and restocking logic  
- ✅ Revealed valuable prescription and purchasing patterns  
- ✅ Enabled data-driven decision-making in pharmacy operations  

---

## 🧾 Real-Life Application Example

Tamil Nadu Co-operative Pharmacy used analytics to forecast the demand of common fever tablets during a seasonal outbreak, leading to better preparedness and zero wastage.

---
✍️ **Read the Full Blog**  
Check out the detailed blog post here:  
📖 [Pharmacy Sales and Inventory Analytics Using Power BI](https://medium.com/@sowmya.dina2004/tablets-trends-where-healthcare-meets-data-science-74b3b1464ff9) 

