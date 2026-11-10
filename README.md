# 🛍️ Customer Segmentation Analysis — Power BI Dashboard

**Customer Segmentation Analysis** is an end-to-end data analytics project that segments **3,900 US retail customers** into 4 distinct behavioural groups using **K-Means Clustering**. The project covers the full pipeline — from SQL data extraction and Python-based EDA to machine learning segmentation and a **6-page interactive Power BI dashboard**.

The project transforms raw shopping data into actionable customer insights, helping the client understand **who their customers are, how they behave, and where the biggest revenue opportunity lies**.

---

## 🎯 Project Objective

The primary objective of this project is to build a customer segmentation solution that enables the business to:

- Identify distinct customer groups based on shopping behaviour
- Understand average spending patterns across different segments
- Pinpoint which customer group is the best subscription conversion target
- Support data-driven marketing decisions for each segment
- Visualise customer distribution and behaviour in an interactive dashboard
- Deliver actionable business recommendations to increase subscription revenue

---

## 📌 Key Performance Indicators

The analysis covers the following key metrics:

- 👥 **Total Customers Analysed:** 3,900
- 📋 **Features (Variables) Used:** 19
- 🧩 **Customer Segments Identified:** 4
- 💎 **Highest Avg Spend:** USD 80.51 — Premium Buyers
- 🔄 **Loyal Subscribers Avg Spend:** USD 59.49
- 🏷️ **Discount Seekers Avg Spend:** USD 58.92
- 💰 **Budget Shoppers Avg Spend:** USD 39.51
- 📉 **Subscription Gap:** 73% of customers have no subscription
- 📈 **Conversion Opportunity:** 250+ new loyal customers from Discount Seekers

---

## 🔍 Key Insights

### Customer Segments
Using K-Means Clustering (K=4), four distinct customer personas were identified. Premium Buyers have the highest average spend at USD 80.51 and rarely use discounts. Loyal Subscribers spend consistently and are already subscribed. Discount Seekers — the largest actionable group — spend similarly to subscribers but have not subscribed, making them the highest conversion priority.

### Subscription Gap
73% of the client's 3,900 customers have no active subscription. This is the central business problem. The data shows this is not a spending issue — Discount Seekers spend USD 58.92 on average, close to the USD 59.49 Loyal Subscriber average.

### Conversion Opportunity
Discount Seekers (624 customers) show subscriber-like purchase behaviour but are not subscribed. A targeted trial subscription offer to this group alone is estimated to convert **250+ new loyal customers**, significantly improving recurring revenue.

### Seasonal & Category Trends
Purchasing behaviour varies by season, with specific product categories performing stronger in certain periods. The dashboard breaks this down by segment to help the client time their marketing campaigns effectively.

### New vs Returning Customers
The analysis reveals retention patterns across segments, helping the client understand which groups return consistently and which need re-engagement.

---

## 📊 Dashboard Preview

> *6-page interactive dashboard built in Microsoft Power BI*

### Page 1 — Customer Overview
KPI cards showing total customers, average spend, subscription rate, and segment distribution overview.

### Page 2 — Segment Analysis
Side-by-side comparison of all 4 segments — count, average spend, discount usage, and subscription status.

### Page 3 — Category & Product Performance
Top purchased items and categories broken down by customer segment.

### Page 4 — Seasonal Trends
Purchase frequency and spend behaviour across seasons for each segment.

### Page 5 — Subscription Analysis
Subscribed vs non-subscribed breakdown, gap analysis, and Discount Seeker conversion opportunity.

### Page 6 — Action Plan
Data-backed marketing recommendations per segment — what to do, who to target, and why.

> 📌 Add your Power BI dashboard screenshots here:
> ```
> ![Page 1](Page1.png)
> ![Page 2](Page2.png)
> ![Page 3](Page3.png)
> ```

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `customer_segmentation.ipynb` | Full Python notebook — EDA, K-Means clustering, visualisations |
| `README.md` | Project documentation |

> Power BI dashboard (.pbix) and presentation (.pptx) available on request.

---

## 🛠️ Tools & Technologies

- Python (pandas, numpy)
- scikit-learn (StandardScaler, KMeans)
- matplotlib & seaborn
- MySQL & phpMyAdmin
- Microsoft Power BI
- DAX & Power Query
- Google Colab
- Microsoft PowerPoint

---

## 📋 Dashboard Features

### Customer Segmentation Overview
Provides a high-level breakdown of:
- 4 customer segments with names and descriptions
- Average spend per segment
- Subscription rate per segment
- Count of customers in each group

### Behavioural Analysis
Focuses on:
- Discount usage patterns
- Purchase frequency
- Category preferences
- Seasonal buying behaviour

### Subscription Gap Analysis
Provides insights into:
- Overall subscription rate (27% subscribed, 73% not)
- Segment-level subscription breakdown
- Conversion opportunity sizing for Discount Seekers
- Revenue impact estimate of conversion

---

## 💡 Business Value

This project helps decision-makers quickly identify:

- Which customers are the most valuable and how to retain them
- Where the biggest subscription conversion opportunity lies
- How to market differently to each of the 4 segments
- Which seasons and categories drive the most purchases
- How to prioritise marketing budget for maximum ROI

By identifying the Discount Seekers as the top conversion target, the client can run a focused trial subscription campaign instead of spending budget on all 73% of non-subscribers — making their marketing significantly more efficient.

---

## 👩‍💻 Author

**Mehtab Bibi**

Data Analyst | Dubai, UAE | SQL | Python | Power BI | Machine Learning

*DataMites Certified Data Analyst — NASSCOM Accredited | 2026*
