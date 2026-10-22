# FitnessHub Subscription Analytics Report (Tableau Edition)

## Executive Summary
This repository contains a comprehensive data analysis of FitnessHub's customer lifecycle, revenue health, and acquisition sustainability across the 2024 and 2025 streaming cohorts using Tableau. 

### Key Business Insights

#### 1. Customer Cohort Analysis (Retention & Churn Cliff)
* **The Problem:** Customers typically cancel their subscriptions after **3 to 4 months** of joining the platform. 
* **The Insight:** The cohort matrix heatmap reveals a sharp, consistent drop-off (roughly 40% churn) between Month 3 and Month 4. This indicates that while the onboarding phase is successful, user engagement drops steeply once the initial novelty of the personalized workout plans wears off.

#### 2. 12-Month Revenue Forecast
* **The Trend:** The expected subscription revenue over the next 12 months shows **strong, steady upward growth** but highlights operational vulnerabilities. 
* **Seasonality:** Yes, the forecast shows clear evidence of **12-month seasonality**. There is a predictable, massive revenue spike every **January** (the "New Year's Resolution" effect), followed by a minor dip in late spring and a secondary, smaller surge in early autumn (September).

#### 3. CAC vs. LTV Break-Even Analysis
* **2024 Cohort Break-Even:** Took **7 months** to recover customer acquisition costs.
* **2025 Cohort Break-Even:** Took **10 months** to reach the break-even point.
* **Strategic Takeaway:** The time-to-recover CAC is lengthening. This indicates that while acquisition costs are rising or retention is shortening, the current strategy is becoming **unsustainable** over the long run unless immediate adjustments are made to improve mid-funnel retention.

---

## Repository Structure
fitness-subscription-analytics/
│
├── README.md                          # Executive brief and business insights
├── Fitness_Hub_Workbook.twbx          # Packaged Tableau Workbook (Data + Layout)
├── data/
│   └── Fitness_Subscriptions_Dataset.xlsx  # Cleaned primary data layer
└── screenshots/
    ├── cohort_analysis.png            # Visual matrix showing retention patterns
    ├── revenue_forecast.png           # 12-month trendline with confidence bands
    ├── cac_vs_ltv.png                 # Break-even cross-over chart
    └── data_model.png                 # Logical relationship layer screenshot
