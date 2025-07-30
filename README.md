# Stay Connected: Insights to Power Telecom Customer Retention – Final Project (Purwadhika Group Beta)

This project aims to analyze the customer behavior of a telecommunications company and identify the key factors contributing to customer churn. Through a combination of data preprocessing, exploratory data analysis, and visual storytelling, we provide strategic insights and actionable recommendations to help reduce churn and improve customer retention.

---

## Objective
To answer the following business questions:
1. **Who are the customers most likely to churn (based on behaviours?**
2. **Do product combinations (add-ons) impact churn?**
3. **What is the demographic profile of churned customers?**
4. **What strategies can reduce churn based on data-driven insights?**

---

## Dataset

The dataset is sourced from a fictional telecom company and contains information such as:

- Customer demographics (gender, age, dependents, etc.)
- Service subscriptions (phone, internet, streaming services)
- Contract type and tenure
- Monthly and total charges
- Churn flag (Yes/No)
---

## Data Preparation

We conducted several preprocessing steps to clean and structure the data:

- **Handling Duplicates:** Removed identical rows to ensure data quality.
- **Missing Value Treatment:** Imputed or removed rows with missing data (e.g., `TotalCharges` with blank values).
- **Dropping Anomalies/Outliers:** Excluded records with zero tenure or suspicious charge values.
- **Feature Engineering:** Created new features (e.g., total add-ons, grouped service types) for deeper analysis.

---

## Exploratory Data Analysis

We broke down the analysis into several perspectives:

### 1. **Demographics vs Churn**
- Senior Citizens and single individuals have higher churn rates.
- Customers without dependents and those living alone are more likely to churn.

### 2. **Contract & Tenure**
- Month-to-month contract users show significantly higher churn.
- Customers with shorter tenure churn more often.

### 3. **Internet Service & Add-Ons**
- Customers who only subscribe to internet without add-ons have a higher churn rate.
- Certain combinations of add-ons correlate with lower churn.

### 4. **Phone Service**
- Users with multiple lines tend to churn less than those with a single line.

### 5. **Charges & Payment Behavior**
- Higher churn in customers with mid-to-high monthly charges and electronic payment methods.
- Customers with paperless billing also show a greater tendency to churn.

---

## Key Takeaways

- Customers with no contract (month-to-month), no add-ons, and lower tenure are most at risk of churning.
- Senior citizens and individuals living alone need more personalized retention strategies.
- Bundled service offerings with streaming, security, or tech support can reduce churn.
- Payment method and billing type influence churn—electronic payments and paperless billing show higher churn tendencies.

