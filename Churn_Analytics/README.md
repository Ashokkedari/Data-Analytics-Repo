# 📊 Customer Churn Analytics & Prediction Dashboard

## 📝 1. Project Overview
This dashboard provides a comprehensive analysis of customer retention patterns and future churn risks. By integrating historical data with predictive modeling, it allows businesses to transition from **reactive problem-solving** to **proactive retention strategies**.

---

## 🛠 2. Tech Stack
* **Power BI Desktop:** Core platform for visual orchestration and reporting.
* **Power Query:** Data transformation, cleaning, and profiling.
* **DAX (Data Analysis Expressions):** Created complex measures for *Churn Rate %*, *Predicted Churners*, and dynamic rankings.
* **Data Modeling:** Implemented a **Star Schema** to connect demographics, geography, and service subscriptions.
* **File Formats:** `.pbix` (Interactive Report) and `.png/.jpg` (Documentation).

---

## 📂 3. Data Source
The analysis is based on a dataset of **824 customers** featuring:
* **Demographics:** Gender, Age Group, and Geographic State.
* **Account Info:** Tenure (months), Contract Type (Month-to-month, 1-Year, 2-Year), and Payment Methods.
* **Services:** Internet Service, Online Security, Device Protection, and Paperless Billing.
* **Financials:** Monthly Charges and Total Revenue.

---

## 🚀 4. Features & Highlights

### 🎯 Business Problem
Organizations often lose revenue because they cannot identify **why** or **when** a customer will leave. This project addresses:
* Which demographics (Age/Gender) are highest risk?
* How do contract types impact loyalty?
* Which missing services correlate most with churn?

### 🥅 Goal of the Dashboard
1.  **Explains the Past:** Visualizes historical drivers and trends.
2.  **Predicts the Future:** Specifically identifies **378 high-risk customers** for immediate intervention.

---

## 🖼 5. Visual Walkthrough

### **Dashboard 1: Historical Summary**
* **KPI Ribbon:** Real-time view of Total Customers (824), Total Churn (234), and **Churn Rate (28%)**.
* **Age Risk:** Identification of the **61+ age group** as the most volatile segment (32% churn).
* **Churn Drivers:** Pie chart highlighting **Competitors (41.88%)** as the primary reason for exit.
* **Service Heatmap:** Shows high churn correlation for users **without** Online Security or Backup.

![Summary Dashboard](Screenshot%202026-01-31%20110052.jpg)

### **Dashboard 2: Prediction (Future Outlook)**
* **Risk List:** A detailed Customer ID table for the sales team to target at-risk users.
* **Tenure Risk:** Highlights the "Danger Zone"—**26%** of predicted churners are in their first 6 months.
* **Revenue Impact:** Quantifies the potential loss from predicted churners.

![Prediction Dashboard](Screenshot%202026-01-31%20110116.jpg)

---

## 💡 6. Business Impact & Insights
* **Retention Strategy:** Focus on "New Joiner" incentives to stabilize customers in the 0–6 month window.
* **Product Bundling:** Promote **Online Security** as a core feature, as it strongly correlates with long-term retention.
* **Geographic Focus:** Priority intervention required in **Uttar Pradesh** and **Haryana** due to high churn volumes.
