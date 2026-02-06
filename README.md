# 🏦 Banking Risk Analysis Project

## 📌 Project Overview

This project focuses on **end-to-end banking risk analysis** using customer-level financial data. The goal is to identify **high-risk customer segments**, understand the **key drivers of financial risk**, and translate analytical findings into **actionable business recommendations**.

The project closely mirrors **real-world banking use cases**, including:

* Credit risk assessment
* Loan approval support
* Portfolio risk monitoring
* Risk-based customer segmentation

> **Outcome:** A recruiter-ready project combining **Python-based EDA**, **statistical insights**, and an **interactive Power BI dashboard**.

---

## 📂 Dataset Summary

* **Total Records:** 3,000 customers
* **Total Features:** 25
* **Data Type:** Structured (Numerical + Categorical)
* **Granularity:** Individual banking customers

### 🔹 Feature Categories

**Customer Demographics**

* Client ID, Name, Age, Gender, Nationality, Occupation, Location ID

**Banking Relationship Information**

* Bank Tenure (Joined Bank)
* Banking Contact Type
* Fee Structure
* Loyalty Classification

**Financial Attributes**

* Estimated Income
* Bank Loans & Deposits
* Credit Card Balance
* Savings & Checking Accounts
* Foreign Currency Accounts
* Business Lending

**Risk Indicators**

* Properties Owned
* Number of Credit Cards
* **Risk Weighting (Target Variable)**

---

## 🎯 Business Problem

Banks face continuous exposure to **credit and financial risk** due to customer borrowing behavior, asset ownership, and income stability.

This project aims to answer:

* Which customers carry **higher financial risk**?
* How do **income, loans, and deposits** influence risk?
* Do **loyal and premium customers** exhibit lower risk?

---

## 🧹 Data Quality & Preprocessing

### ✔ Data Quality Checks

* No missing values detected
* Correct data types across numerical and categorical columns
* Unique Client IDs (no duplicate records)

### ✔ Preprocessing Steps

* Converted bank joining dates into **customer tenure**
* Encoded categorical features for analysis
* Checked numerical distributions for skewness and outliers

> The dataset was found to be **clean and analysis-ready**.

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Demographic Insights

* Majority of customers fall in the **working-age group (30–60)**
* Certain occupations show **higher loan and credit exposure**
* Property ownership strongly correlates with **lower risk**

### 🔹 Financial Behavior Insights

**Income vs Risk**

* Lower income combined with **high loan exposure** leads to higher risk
* High income alone does not ensure low risk without strong savings

**Loans & Credit Cards**

* Risk increases with:

  * Higher number of credit cards
  * Larger outstanding credit card balances
  * Heavy dependence on bank loans

**Assets & Savings**

* Customers with:

  * Higher deposits
  * Strong savings balances
  * Multiple properties
    exhibit **lower risk profiles**

---

## ⚠ Risk Weighting Analysis

Risk Weighting is the **core dependent variable** in this analysis.

### Observed Patterns

**High-Risk Customers**

* High loan exposure
* Low savings-to-loan ratio
* Multiple credit cards with high balances

**Low-Risk Customers**

* Strong deposit base
* Long-term banking relationship
* Higher loyalty tiers (Gold / Platinum)

> Risk is driven by a **combination of income stability, liabilities, and asset ownership**.

---

## 👥 Customer Segmentation (Risk Perspective)

Customers were segmented into three risk-based groups:

### 🟢 Low-Risk / High-Value

* High income
* High deposits & savings
* Low loan dependency

### 🟡 Medium-Risk

* Balanced income and loans
* Moderate savings

### 🔴 High-Risk

* High loan-to-income ratio
* High credit card utilization
* Low asset ownership

> This segmentation supports **risk-based pricing, monitoring, and targeted banking strategies**.

---

## 📈 Dashboard & Visual Analytics (Power BI)

The Power BI dashboard provides **executive-level visibility** into banking risk.

### Key Dashboard Features

* Portfolio KPIs (Total Customers, Avg Risk, Total Loans & Deposits)
* Risk distribution across customers
* Income vs Risk scatter analysis
* Loan vs Deposit comparison by risk category
* Credit card exposure and property ownership analysis
* Loyalty classification vs risk

### 📌 Dashboard Preview

*(Add screenshots in your GitHub repo and reference them here)*

```md
![Banking Risk Dashboard](images/banking_dashboard.png)
```

---

## 📌 Key Insights Summary

* **Total Customers:** 3,000
* **High-Risk Customers:** 942 (31.4%)
* **Medium-Risk Customers:** 2,058 (68.6%)
* **Loan exposure** is the strongest risk driver
* **Asset ownership** significantly reduces risk
* **Estimated Income** shows strong correlation with risk weighting

---

## 🧠 Risk Management Recommendations

### 🔴 High-Risk Customers (Risk Level 3+)

* 942 customers (31.4%)
* High average loan exposure
* **Action:** Stricter credit approval and frequent monitoring

### 💳 Credit Card Risk

* 25% customers hold high credit card balances
* **Action:** Review limits and repayment structures

### 🕒 New Customers (Tenure < 3 years)

* Higher proportion of high-risk profiles
* **Action:** Probation period with enhanced monitoring

### 👶👴 Age-Based Risk

* Young (<30) and Senior (>70) customers show higher risk
* **Action:** Develop age-specific risk models

---

## 🧰 Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Jupyter Notebook**
* **Exploratory Data Analysis (EDA)**
* **Statistical Analysis**
* **Power BI (Dashboard & DAX)**

---


---



📬 **Author:** Karan Singh
📊 **Role Target:** Data Analyst / Risk Analyst / Business Analyst

> *This project demonstrates my ability to translate raw banking data into meaningful risk insights and business decisions.*
