# 🚀 Wolt User Insights & Growth Strategy – Data Science Project

This project dives deep into user-level behavioral data for **Wolt**, a food delivery platform operating across Europe. The goal is to uncover key business insights and growth levers through exploratory data analysis and visualization.

---

## 🏢 Business Context

Wolt connects customers with local restaurants and stores via mobile and web platforms. As a growth-stage company in the on-demand delivery space, Wolt's success relies on:

- High **activation rates** from new users
- Strong **repeat behavior** to maximize lifetime value (LTV)
- Efficient targeting of user segments by **device** and **location**

---

## 🎯 Project Goals

- Understand **where users drop off** in the lifecycle
- Quantify **retention and repeat purchase patterns**
- Segment users by **device** and **country** to find high-LTV cohorts
- Provide **data-driven recommendations** to drive growth

---

## 📦 Dataset Overview

- **Total users**: 21,983
- **Columns** include: registration country, preferred device, purchase count, timestamps of first/last purchase, revenue metrics, and behavioral features like meal timing and average delivery distance.

---

## 🛠️ Tools Used

- **Python**
- `pandas`, `numpy` – data wrangling  
- `matplotlib`, `seaborn` – visualizations  
- **Jupyter Notebook** for analysis

---

## 🔍 Key Insights

| Area              | Insight |
|------------------|---------|
| **Activation**    | 45% of users never placed an order. Payment method validity strongly influences activation rate. |
| **Retention**     | 61.7% of users who ordered within 3 days of signup made repeat purchases — but even late converters (>10 days) showed strong retention (65.3%). |
| **Revenue**       | Denmark leads in revenue and activation. iOS users base is the highest around 9700 but Web users spend more per order. |
| **Behavior**      | Lunch and dinner dominate purchase patterns. Most orders happen midday or early evening. |

---

## ✅ Recommendations

- **Improve payment method onboarding** to increase conversion from registrations.
- Launch **targeted campaigns** for one-time users within 3–7 days post first order.
- Focus **premium loyalty and upsell offers** on iOS users.
- Localize acquisition and onboarding flows in **underperforming countries**.
- Use **purchase frequency** to flag potential churn risk.

---


## 📁 Project Structure

├── data/
│ └── dataset.csv
├── notebooks/
│ └── wolt_analysis.ipynb
├── visuals/
│ ├── user_funnel_chart.png
│ ├── device_revenue_chart.png
│ └── repeat_rate_by_country.png
├── Wolt_User_Insights_Presentation.pptx
└── README.md
