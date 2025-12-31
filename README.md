# 📊 Working Capital Optimization & Predictive Analytics

## 📌 Project Overview
Working Capital Optimization focuses on efficiently managing **Accounts Receivable (AR)** and **Accounts Payable (AP)** to ensure healthy cash flow and liquidity.  
---

## 🎯 Objectives
- Forecast **customer payment weeks** (Accounts Receivable)
- Predict **supplier payment weeks** (Accounts Payable)
- Analyze weekly inflows vs outflows to compute **Working Capital**
- Identify periods of **liquidity risk or surplus**
- Enable data-driven decisions for payment prioritization

---

## 🗂️ Data Description

### Accounts Receivable (AR)
- Customer ID, Customer Name, Region  
- Invoice ID, Due Date, Payment Date  
- Credit Limit, Dunn Level  
- Total Open Amount (Local & USD)  
- Payment Terms, Business Year  

### Accounts Payable (AP)
- Supplier ID, Supplier Category  
- Invoice Number, Invoice Amount  
- Invoice Date, Posting Date  
- Net Due Date, Payment Date  
- Invoice Status, Overdue Indicator  
- Spend Category, Late Payment Fees  

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, pyodbc  
- **Database:** SQL Server (AWS RDS)  
- **Cloud Platform:** AWS (S3, RDS)  
- **Visualization:** Tableau (Tableau Public)

---

## 🔍 Methodology

### 1. Exploratory Data Analysis (EDA)
- Identified payment patterns, delays, and anomalies  
- Analyzed customer and supplier behavior across regions and payment terms  

### 2. Feature Engineering
- Payment lag calculations  
- Weekly aggregation of receivables and payables  
- Currency normalization to USD  

### 3. Predictive Modeling
Built and evaluated multiple regression models:
- Linear Regression  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- K-Nearest Neighbors (KNN)  
- Support Vector Regressor (SVR)  

### 4. Working Capital Computation
- Aggregated AR and AP on a **weekly basis**  
- Calculated:  
  **Working Capital = Total Receivables − Total Payables**  
- Identified weeks with **positive and negative liquidity**

---

## 📈 Tableau Dashboards
- AR vs AP weekly trends  
- Payment delay analysis  
- Customer and supplier risk segmentation  
- Working capital movement visualization  

📌 Dashboards were shared as **images or Tableau Public links** to ensure **no edit access**.

---

## ✅ Key Outcomes
- Improved visibility into **future cash positions**  
- Enabled proactive **payment scheduling decisions**  
- Demonstrated how predictive analytics supports **liquidity planning**  
- Reduced reliance on reactive cash-flow management  

---

## 📚 Key Learnings
- End-to-end financial data modeling  
- Applying machine learning to real-world finance problems  
- Translating analytical insights into executive-ready dashboards  
- Integrating SQL, AWS, Python, and Tableau in a unified workflow  

---

## 🚀 Future Enhancements
- Time-series forecasting (ARIMA / Prophet)  
- Real-time ingestion using AWS Lambda  
- Automated alerts for liquidity risk  
- Scenario analysis for payment term optimization  
