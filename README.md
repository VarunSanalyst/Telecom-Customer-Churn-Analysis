# 📉 Telecom Customer Churn Analysis

## 🎯 Objective
To identify the key drivers behind customer churn and provide actionable insights to reduce churn rate in a competitive telecom market. Customer retention is more cost-effective than acquisition, making churn prediction critical.

---

## 📁 Dataset Overview

- *Total Records*: ~7,043 customers
- *Target Variable*: Churn (Yes/No)

### 🔑 Features:
- *Demographics*: Gender, Senior Citizen, Partner, Dependents  
- *Account Info*: Tenure, Contract Type, Monthly Charges, Total Charges, Payment Method  
- *Services*: Phone, Internet, Online Security, Online Backup, Device Protection, Streaming, Tech Support  

---

## 🧹 Data Preprocessing

- Filled missing TotalCharges values (11 records) using the mean.
- Handled Tenure = 0 as new customers (retained).
- Transformed binary variables (e.g., SeniorCitizen: 0/1 → No/Yes).
- Converted categorical data for modeling and visualization.

---

## 📊 Key Insights

### 🔻 Churn Overview
- Overall Churn Rate: *26.54%*  
- Around 1 in 4 customers leave — high for telecom industry

### 👵 Demographic Drivers
- *Senior Citizens*: ~42% churn  
- *With Dependents: 15% churn | **Without*: 31%  
- *Without Partners*: Higher churn

### 📞 Service Usage Patterns
- *No Internet*: Less churn  
- *Fiber Optic Internet*: ~42% churn  
- *Online Security/Tech Support Absent*: ~35% churn  
- *Streaming/Multiple Lines*: Absence → higher churn

### 🧾 Billing and Contract
- *Month-to-Month Contracts*: ~43% churn  
- *2-Year Contracts*: ~3% churn  
- *Electronic Check*: ~45% churn  
- *Auto Pay (Credit/Bank)*: ~15–18% churn

### ⌛ Tenure & Charges
- *0–2 Months Tenure*: ~50% churn  
- *Tenure > 1 Year*: More stable  
- *High Monthly Charges (~$70)*: ~38% churn

---

## ✅ Recommendations

1. *Retention focus during first 3 months*
2. *Promote long-term contracts (annual or biannual)*
3. *Bundle key services* (Online Security, Tech Support)
4. *Target high monthly-charge customers with loyalty offers*
5. *Discourage electronic check payments (promote auto-pay)*

---

## 🧰 Tools Used

- *Python / Pandas* – Data preprocessing 
- *Jupyter Notebook* – EDA and modeling 

---

## 🚀 Author

*Varun S*  
Aspiring Data Analyst | Power BI & SQL Enthusiast  
📫 www.linkedin.com/in/varun-s-b4842b29b
📧 varunsgowda2001@gamil.com


## ⭐ If you like this project, give it a star!
