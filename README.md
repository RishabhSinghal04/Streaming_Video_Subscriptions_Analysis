# Streaming Video Subscriptions Analysis

## 📌 Overview
This project focuses on analyzing subscription data to generate actionable business insights. It covers customer churn, rejoin behaviour and monthly recurring revenue (MRR). The goal is to help businesses understand customer behaviour, improve retention, and forecast revenue.

**Source**: https://mavenanalytics.io/data-playground/streaming-video-subscriptions

## ✨ Key Features
- **Data Preparation**: Cleaning and structuring raw subscription data.
- **Customer Metrics**: Active vs. canceled customers, churn rate, rejoin rate.
- **Revenue Metrics**: Monthly Recurring Revenue.
- **Rejoin Analysis**: Identifies customers who cancel and later rejoin.

## 🛠️ Technologies Used
- **Python 3**
- **Pandas**: Data manipulation and cohort analysis
- **NumPy**: Efficient numerical/statistical calculations
- **Jupyter Notebook** (optional): Interactive exploration

## ⚙️ Data Preparation Steps
1. **Load dataset**: Import CSV file.
2. **Parse dates**: Convert `created_date` and `canceled_date` into datetime format.
3. **Create status column**: Label each record as `Active` or `Canceled`.
4. **Add rejoin flag**: Mark customers who canceled and later rejoined.
5. **Convert subscription_cost**: Ensure numeric type (`float`) for calculations, with optional currency formatting for reporting.

## 📊 Insights Steps
1. **Customer Health**:
   - Count active vs. canceled customers.
   - Calculate churn rate and rejoin rate.
2. **Revenue**:
   - Calculate Monthly Recurring Revenue (MRR).