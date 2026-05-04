# 📊 CRM Business Intelligence Dashboard

This repository contains the advanced Power BI analytical dashboard for the CRM project. It provides a 360-degree view of sales performance, pipeline health, and operational efficiency through complex data modeling and custom DAX measures.

## 🌟 Key Features

The report is structured into **three analytical pages**:

1.  **Executive Dashboard:** High-level strategic KPIs including Revenue Growth, Market Share by Industry, and AI-driven Lead Quality distribution.
2.  **Sales Pipeline Analysis:** Deep dive into deal aging, sales velocity, and weighted revenue forecasting using probability-based calculations.
3.  **Team Productivity & Support:** Monitoring sales representative activities (Email/Tasks) and customer support effectiveness (Ticket resolution rates).

## 🛠️ Technical Specifications

### Data Modeling
*   **Star Schema:** Optimized relationships between Fact tables (`Deals`, `Activities`, `Emails`, `Tickets`) and Dimension tables (`Users`, `Companies`, `Leads`, `Calendar`).
*   **Time Intelligence:** Custom date table implementation for Month-over-Month (MoM) and Year-over-Date (YTD) comparisons.

### Key DAX Measures
The dashboard implements over **30 custom measures**, including:
*   **Sales Velocity:** `(Open Deals * Avg Value * Win Rate) / Sales Cycle Length`
*   **Weighted Pipeline:** Probability-adjusted revenue forecast.
*   **Lead Conversion Rate:** Success ratio from Prospect to Customer.
*   **Churn Risk Score:** Identification of inactive high-value accounts.

## 📈 Visualizations Used
To ensure high-density information without cluttering, this report prioritizes advanced visuals over simple cards:
*   **Ribbon Charts:** For tracking industry ranking changes over time.
*   **Scatter Plots:** For correlating deal value with winning probability.
*   **Treemaps:** For hierarchical breakdown of market share.
*   **Funnels:** For multi-stage pipeline conversion analysis.

## 🚀 How to Use
1.  Ensure you have **Power BI Desktop** installed.
2.  Open the `CRM_Analytics.pbix` file.
3.  Go to `Home > Transform Data > Data Source Settings`.
4.  Update the connection string to point to your **MySQL** database.
5.  Click **Refresh** to sync the latest data from the CRM.

---
**Developed by [Your Name/Amen Allah Mselmi]**
