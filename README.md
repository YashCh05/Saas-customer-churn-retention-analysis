# SaaS Customer Churn & Retention Analysis

## 📌 Project Overview
This project presents an end-to-end analysis of customer churn and retention for a SaaS platform. The objective is to understand historical churn behavior, identify early warning signals, and provide actionable insights that can help reduce customer attrition and improve retention strategies.

The analysis combines customer lifecycle data, product usage behavior, support experience, and risk segmentation to simulate a real-world SaaS analytics use case.

---

## 🎯 Business Problem
Customer churn directly impacts revenue stability and long-term growth for SaaS businesses.

**Core Question:**
> How can a SaaS company identify historical churn patterns and detect early engagement and inactivity signals to proactively retain at-risk customers?

This project focuses on identifying **when churn happens**, **why it happens**, and **which customers should be prioritized for retention efforts**.

---

## 📊 Datasets Used
The analysis is based on multiple related datasets representing a realistic SaaS environment:

- **Accounts** – Customer profile, plan tier, trial status, tenure, churn flag  
- **Subscriptions** – Plan lifecycle and billing information  
- **Feature Usage** – Product usage volume, feature adoption, error counts  
- **Support Tickets** – Resolution time, response time, escalations  
- **Churn Events** – Historical churn occurrences  

All datasets are linked using `account_id` as the primary key.

---

## 🛠️ Tools & Technologies

### 1. Python (with SQL)
- Data cleaning and data type correction
- Feature engineering and metric creation
- SQL (via SQLite) used to answer business questions:
  - Churn by tenure
  - Engagement vs churn
  - Inactivity analysis
  - Risk segmentation

### 2. Excel
- Used for quick validation and exploratory checks
- Raw CSV files opened directly
- Basic data type corrections
- Simple pivot tables and charts for sanity checks

### 3. Power BI
- Final data modeling and visualization
- Account-level data model using `account_id`
- Single executive dashboard for storytelling and insights

---

## 🔍 Project Workflow

1. Defined churn as **historical churn** (accounts that churned at least once)
2. Cleaned and transformed data using Python
3. Aggregated event-level data to account level
4. Performed SQL-based analysis to answer business questions
5. Designed churn risk segmentation (Low / Medium Risk)
6. Built an executive Power BI dashboard with KPIs, charts, and slicers

---

## 📈 Key Findings

- **Total Accounts:** 500  
- **Historical Churn Rate:** 70.40%  
- **Average Customer Tenure:** 193.92 days  
- **Medium Risk Accounts:** 17  
- **Average Days Since Last Usage:** 16.31 days  
- **Average Support Resolution Time:** 36.24 hours  

### Key Insights:
- Churn is highest during the **first 30 days** of the customer lifecycle
- Higher product engagement strongly correlates with better retention
- Usage inactivity is one of the strongest early warning indicators of churn
- Medium-risk customers represent the primary group for proactive retention efforts
- Churn exposure varies across plan tiers, indicating revenue risk areas

---

## 📊 Dashboard Highlights
The Power BI dashboard focuses on:
- Historical churn by tenure bucket
- Engagement vs churn behavior
- Inactivity signals and early warning indicators
- Churn risk segmentation
- Churn exposure by plan tier

Slicers included:
- Plan Tier
- Industry
- Country
- Trial Status

#<img width="789" height="508" alt="Screenshot 2026-02-03 222313" src="https://github.com/user-attachments/assets/544904e9-aa39-4d53-8afb-d0343a5808c5" />

---

## 💡 Business Recommendations

- Strengthen onboarding to reduce early-stage churn
- Monitor usage inactivity to trigger early interventions
- Prioritize medium-risk customers for retention campaigns
- Encourage multi-feature adoption to improve engagement
- Use historical churn patterns to guide proactive retention strategies

---

---

## 📌 Conclusion
This project demonstrates a complete analytics workflow using Python, SQL, Excel, and Power BI to solve a real-world SaaS churn problem. The insights generated are designed to support data-driven decision-making for product, growth, and customer success teams.

---

## 👤 Author
**Yash**


