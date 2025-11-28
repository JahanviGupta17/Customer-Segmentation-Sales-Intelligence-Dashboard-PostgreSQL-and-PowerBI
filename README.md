# <p align="center"> DASHBOARD OVERVIEW
<p align="center">
  <img src="./images/dashboard%20bi.png" alt="Dashboard Preview" width="100%">
</p>

# 📑 Table of Contents

1. [Project Overview](#1-project-overview)
2. [Key Performance Indicators (KPIs)](#2-key-performance-indicators-kpis)
3. [Dataset Summary](#3-dataset-summary)
4. [Data Pipeline](#4-data-pipeline)
5. [Exploratory Data Analysis](#5-exploratory-data-analysis)
6. [Customer Segmentation Insights](#6-customer-segmentation-insights)
7. [Dashboard Insights](#7-dashboard-insights)
8. [Business Recommendations](#8-business-recommendations)
9. [Tech Stack](#9-tech-stack)
10. [Project Structure](#10-project-structure)
11. [How to Run the Project](#11-how-to-run-the-project)
12. [Conclusion](#12-conclusion)
---

#  1. Project Overview

**Problem Statement:**  
The business needed to **understand its sales performance and customer behavior** to increase revenue, reduce churn, and improve engagement. The existing data was scattered, and insights were not actionable.  

**Objective:**  
- Identify high-value customers and at-risk customers  
- Segment customers based on purchasing behavior  
- Analyze sales trends over time to detect peak and low periods  
- Provide actionable insights to improve revenue and retention  

**What I Did:**  
- Cleaned and transformed sales and customer data from PostgreSQL and Excel  
- Calculated **RFM scores** for customer segmentation  
- Built **interactive Power BI dashboards** for visual analysis  
- Generated a **full report with actionable recommendations** for business stakeholders  
---

#  2. Key Performance Indicators (KPIs) – Executive Highlights

### Sales Performance

* **Total Sales:** ₹1.06 Cr – Indicates strong revenue performance with seasonal peaks.
* **Average Order Value (AOV):** ₹531 – Healthy purchase size with upsell potential.
* **Total Orders:** 19,959 – Reflects strong customer activity and engagement.

### Customer Insights

* **Total Customers:** 4,339 – Diverse and active customer base.
* **Segment Breakdown:**

  * **Champions (43.97%)** – Core revenue drivers, high engagement.
  * **Loyal Customers (14.5%)** – Moderate revenue, steady growth potential.
  * **Potential (9%)** – Opportunities for growth through targeted campaigns.
  * **Needs Attention (7.1%)** – At-risk customers requiring retention focus.

### High-Value Customers

* **Top Customers Revenue Contribution:** ₹15.37 Lakh from 7 top customers
* **Revenue Range per Top Customer:** ₹80k–₹2.8L
* **Strategic Focus:** Personalized engagement and loyalty programs to maximize retention.

### Actionable Insight

* Revenue is concentrated in Champions and top customers → high-value segment-focused strategy recommended.
* Potential and Needs Attention segments present significant revenue growth opportunities.
---

#  3. Dataset Summary

* Customer transaction records including order amounts, counts, and timestamps
* Customer demographics and segment labels
* Sales time-series for trend analysis

**Data Sources:**
* PostgreSQL database for transactional data
* Excel for preprocessing, cleaning, and RFM calculations
---

#  4. Data Pipeline

### Data Cleaning
* Removed duplicate and blank entries
* Standardized customer segment labels
* Handled missing or inconsistent order values

### Feature Engineering
* Computed **Average Order Value (AOV)**
* Generated **RFM scores** for customer segmentation
* Identified **high-value customers**

### Data Transformation
* Aggregated data at customer and segment level
* Created monthly and quarterly sales trends for visualization
---

#  5. Exploratory Data Analysis
**Key Insights:**
* Monthly sales fluctuate with peaks during specific periods
* Champions segment generates the highest revenue per customer (~₹6,000)
* Loyal and Potential segments contribute moderately
* Needs Attention segment has low engagement and monetary value

**Visualizations Included:**
* Monthly sales trends
* Segment-wise customer and revenue distribution
* RFM analysis charts
* Top customer revenue visualizations
---

#  6. Customer Segmentation Insights

**Segment Analysis:**
* **Champions:** High engagement, high revenue → retention focus
* **Loyal Customers:** Moderate engagement, steady revenue → upsell/cross-sell focus
* **Potential:** Low engagement, high growth opportunity → marketing campaigns
* **Needs Attention:** Low engagement, low revenue → proactive retention campaigns

**RFM Patterns:**
* Champions: High frequency, high monetary, low recency
* Needs Attention: Low frequency, low monetary, high recency
* Potential: Low frequency, moderate monetary, high recency
---

#  7. Dashboard Insights (Power BI)
* **Sales Trend:** Monthly fluctuations with peak periods identified
* **Customer Segmentation:** Champions dominate revenue share; Needs Attention presents growth potential
* **Top Customers:** High revenue contributors identified for targeted campaigns
* **RFM Analysis:** Visualizes frequency, monetary, and recency patterns across segments
---

#  8. Business Recommendations

### Retention Strategy
* Reward Champions with loyalty programs
* Engage Needs Attention customers through targeted offers
* Nurture Potential segment to increase order frequency

### Revenue Strategy
* Upsell and cross-sell to Loyal Customers
* Focus marketing on top-performing customers
* Align inventory and promotions with sales trend patterns

---

#  9. Tech Stack
* **PostgreSQL:** Data storage and querying
* **Excel:** Data cleaning, preprocessing, and RFM calculation
* **Power BI:** Interactive dashboards and visualization
* **Git & GitHub:** Version control
---

#  10. Project Structure
```
project/
│── data/                  # Raw and cleaned datasets
│── powerbi/               # Power BI dashboard files
│   └── sales_dashboard.pbix
│── images/                # Dashboard preview and visualizations
│── README.md
```

#  11. Conclusion

This project showcases **end-to-end sales analytics**:

* Customer segmentation using RFM analysis
* Sales trend and top customer insights
* Actionable business recommendations
* Power BI dashboard for executive reporting
* Data engineering with PostgreSQL and Excel

**Impact:** Provides actionable insights for **driving revenue growth and improving customer retention**.

