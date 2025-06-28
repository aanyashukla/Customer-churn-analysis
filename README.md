# 📊 Customer Churn Analysis

This project explores customer churn behavior using the **Telco Customer Churn** dataset. 
The goal is to identify key factors that contribute to customer churn and derive actionable business insights that can improve customer retention.

---

## 📁 Dataset Overview

- **Source**: `Telco-Customer-Churn.csv`
- **Total Records**: ~7,000
- **Target Variable**: `Churn` (Yes/No)
- **Key Features**:
  - Customer demographics (gender, senior citizen, tenure)
  - Contract types and billing methods
  - Subscription to services (Internet, Security, Tech Support, Streaming)

---

## 🔍 Analysis Performed

### 🧹 Data Preprocessing
- Converted `SeniorCitizen` from binary to categorical.
- Handled missing values in `TotalCharges` and cast it to float.
- Verified no duplicates or null values remained.

### 📈 Exploratory Data Analysis
- Overall churn rate: **26.54%**
- Visual comparisons using:
  - Pie charts (churn distribution)
  - Count plots (gender, contract type, service usage)
  - Histograms (tenure vs churn)
  - Stacked bar charts (churn % across groups)
  - Multi-subplot views for service categories

---

## 📌 Key Insights

- 📉 **Short-tenure customers (1–2 months)** have the highest churn.
- 👵 **Senior citizens churn more** than non-seniors.
- 📄 **Month-to-month contracts** show significantly higher churn than longer-term contracts.
- 🔐 Lack of services like **OnlineSecurity**, **TechSupport**, and **DeviceProtection** is strongly associated with higher churn.
- 🌐 **Fiber optic users** tend to churn more than DSL users.

---

## 📂 Files Included

- `Customer Churn Analysis.ipynb`: Main notebook with full EDA and insights.
- `Telco-Customer-Churn.csv`: Dataset used for analysis.

---

## ✅ Requirements

- Python ≥ 3.8
- Jupyter Notebook
- Libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`
