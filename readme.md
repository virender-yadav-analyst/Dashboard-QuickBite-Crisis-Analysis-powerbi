# QuickBite Crisis Analysis & Recovery Dashboard

A complete end-to-end analytical project solving the QuickBite 2025 crisis using **EDA, Rating Analysis, Sentiment Analysis, KPI tracking, and a Power BI Recovery Dashboard**.

This README is recreated using the problem statement and analysis requirements from the uploaded documents.

---

## 📖 About the Project
QuickBite, a Bengaluru-based food delivery startup, faced a major crisis in **June 2025** due to:
- Viral social media incident on food safety violations
- A week-long delivery outage during monsoon
- Aggressive competitor campaigns

This led to:
- Sharp decline in daily orders
- Increased cancellations
- Drop in customer satisfaction
- Surge in customer acquisition cost
- Restaurant partners moving to competitors

This project performs **Primary + Secondary Analysis**, evaluates customer & restaurant behavior pre-crisis vs crisis, and builds a Power BI recovery dashboard.

---

## ✨ Features
- Complete Primary Analysis (Based on provided datasets)
- Monthly order trends pre-crisis vs crisis
- City-level decline insights
- High-volume restaurant decline analysis
- Customer sentiment & negative keyword extraction
- SLA, cancellation rate & delivery delay impact
- Revenue loss estimation
- Customer loyalty & churn analysis
- High-value customer behavioral shift study
- Power BI dashboard covering all KPIs
- Secondary analysis insights for strategy & recovery

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib)
- **Power BI** (Visual reports & dashboards)
- **Jupyter Notebook** for exploratory analysis

---


## 🧵 Dataset Description
Based on the dataset metadata and problem statement:
- **Order Data** – order ID, customer ID, restaurant ID, subtotal, discount, delivery fee
- **Customer Data** – demographics, location, lifetime value
- **Restaurant Data** – restaurant type, cuisine, tier, city
- **Rating & Review Data** – customer ratings, text reviews
- **Timeline Data** – classified into: Pre-crisis (Jan–May 2025), Crisis (Jun–Sep 2025)

---

## 📊 Exploratory Data Analysis
Primary analysis tasks completed:
1. **Monthly orders comparison**: Pre-crisis vs crisis decline
2. **Top 5 city groups** with highest order decline
3. **Top 10 high-volume restaurants** with largest order loss
4. **Cancellation trend** analysis across phases
5. **SLA compliance check** – delivery delays worsening?
6. **Month-wise rating fluctuation**
7. **Negative sentiment keyword extraction** (Word Cloud)
8. **Revenue loss estimation** based on transaction values
9. **Customer loyalty impact** – high-rating customers who churned
10. **High-value customer decline** and pattern identification

---

## 🤖 Modeling & Insights
### Sentiment Analysis
- Cleaned review texts
- Extracted polarity & categorised into positive, neutral, negative
- Identified crisis-period negative keyword spikes

### Customer Behavior Insights
- Loyal customers churn linked to delivery delays & food safety concerns
- High-value customers showed increased sensitivity to SLA issues

---

## 📈 Power BI Dashboard
The dashboard includes:
- Pre vs crisis monthly order trends
- City-level decline matrix
- Cancellation & SLA trends
- Restaurant performance summary
- Rating & sentiment analytics
- Revenue loss visualization
- Customer churn & loyalty KPIs
- Word cloud of negative keywords during crisis

---

## 📊 Key Performance Indicators (KPIs)
Based on the Power BI dashboard visuals:

### **Customer & Order KPIs**
- **105.18K Total Customers**
- **54K Customers Lost during Crisis**
- **114K Total Orders (Pre-crisis)**
- **35K Total Orders (Crisis)**
- **~70% decline in monthly orders** from May to June

### **Delivery Performance KPIs**
- **Avg Delivery Time (Overall): 49.82 mins**
- **Pre-crisis Avg Delivery Time: 39.52 mins**
- **Crisis Avg Delivery Time: 60.12 mins**
- **SLA Compliance Rate: 0.56**
- **62% cancellations during crisis vs 38% pre-crisis**

### **Revenue KPIs**
- **Total Revenue: 48.56M**
- **Pre-crisis Revenue: 37.62M**
- **Crisis Revenue: 10.94M**
- **Revenue Drop: -70.92%**
- **Bengaluru, Mumbai & Delhi saw the highest revenue decline**

### **Customer Segmentation KPIs**
- **At Risk Customers: 40.24K (38.26%)**
- **Loyal Customers: 32.52K (30.92%)**
- **New Customers: 14.06K (13.36%)**
- **Lost Customers: 11.15K (10.6%)**

### **Spending Trends**
- Significant drop in average monthly spending after May
- **Pre-crisis avg spend ~7.3M per month**
- **Crisis avg spend ~2.7M per month**

### **City-level Insights**
- Highest order & revenue drop: **Bengaluru**, followed by **Mumbai**
- Kolkata & Ahmedabad had the lowest volumes and smallest declines

---

## 🧾 Results
The KPIs clearly show a severe operational and trust crisis:
- Massive drop in orders, revenue and customer retention
- Delivery performance deterioration directly linked to churn
- Negative reviews and low sentiment intensified during crisis

These insights guide targeted recovery strategies outlined in the dashboard.

- Key metrics summary
- Percentage change calculations
- Sentiment distribution
- Data-driven recommendations

Add screenshots or link to the final report.
[Overview](https://github.com/virender-yadav-analyst/Dashboard-QuickBite-Crisis-Analysis-powerbi/blob/5154537317b86b343dce521b083c53082a02c7eb/Screenshot%202025-11-23%20223822.png)<br>
[Delivery](https://github.com/virender-yadav-analyst/Dashboard-QuickBite-Crisis-Analysis-powerbi/blob/5154537317b86b343dce521b083c53082a02c7eb/Screenshot%202025-11-23%20223835.png)<br>
[Revenue](https://github.com/virender-yadav-analyst/Dashboard-QuickBite-Crisis-Analysis-powerbi/blob/5154537317b86b343dce521b083c53082a02c7eb/Screenshot%202025-11-23%20223848.png)<br>
[Rating and sentiments](https://github.com/virender-yadav-analyst/Dashboard-QuickBite-Crisis-Analysis-powerbi/blob/5154537317b86b343dce521b083c53082a02c7eb/Screenshot%202025-11-23%20223858.png)
---


## 📬 Contact
**Virender yadav**  
Email: virenderyada182@gmail.com  
LinkedIn:[LinkedIn](https://www.linkedin.com/in/virender-yadav-9045a5153/)