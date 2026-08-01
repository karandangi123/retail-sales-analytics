<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Matplotlib-3.x-11557C?style=for-the-badge" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/Seaborn-0.13-444876?style=for-the-badge" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License"/>
</p>

<h1 align="center">🛒 Retail Sales Analytics Report</h1>

<p align="center">
  <i>Transforming retail transaction data into actionable business insights through<br/>customer analytics, product analysis, cohort analysis, and RFM segmentation.</i>
</p>

---

## 📑 Table of Contents

| #  | Section |
|----|---------|
| 1  | [Executive Summary](#-executive-summary) |
| 2  | [Dataset Overview](#-dataset-overview) |
| 3  | [Project Structure](#-project-structure) |
| 4  | [Key Business Questions](#-key-business-questions) |
| 5  | [Key Findings](#-key-findings) |
|    | ↳ [Monthly Performance](#-monthly-performance) |
|    | ↳ [Customer Analysis](#-customer-analysis) |
|    | ↳ [Product Analysis](#-product-analysis) |
|    | ↳ [Country Analysis](#-country-analysis) |
|    | ↳ [Cohort Analysis](#-cohort-analysis) |
|    | ↳ [RFM Customer Segmentation](#-rfm-customer-segmentation) |
| 6  | [Business Recommendations](#-business-recommendations) |
| 7  | [Conclusion](#-conclusion) |
| 8  | [Tech Stack](#-tech-stack) |

---

## 🎯 Executive Summary

### Project Objective

The objective of this project was to analyze historical retail transaction data to understand **sales performance**, **customer purchasing behavior**, **product performance**, **geographical trends**, **customer retention**, and **customer segmentation**. The analysis aims to provide actionable business insights that can support data-driven decision-making and improve overall business performance.

### 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| **Language** | Python |
| **Libraries** | Pandas · NumPy · Matplotlib · Seaborn |
| **Environment** | Jupyter Notebook |
| **Techniques** | Cohort Analysis · RFM Analysis · Business Analytics · Data Visualization |

---

## 📦 Dataset Overview

| Property | Detail |
|---|---|
| **Dataset** | [UCI Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) |
| **Industry** | E-commerce / Retail |
| **Analysis Period** | December 2009 – December 2010 |
| **Customers** | 4,286 |
| **Products** | 4,011 |
| **Countries** | 37 |

---

## 📁 Project Structure

```
online retail/
│
├── 📂 Data/
│   ├── online_retail_II.xlsx          # Raw dataset
│   └── clean_data.xlsx                # Cleaned & preprocessed dataset
│
├── 📂 Notebooks/
│   ├── 01_Ecommerce_EDA.ipynb.ipynb   # Exploratory Data Analysis
│   └── 02_Cohort_RFM_Analysis.ipynb   # Cohort & RFM Segmentation
│
├── 📂 charts/
│   ├── Monthly Revenue Trend.png
│   ├── Month-over-Month Revenue Growth.png
│   ├── Monthly Average Order Value.png
│   ├── Top 10 Customers by Revenue.png
│   ├── Top 10 Products by Revenue.png
│   ├── Top 10 Countries by Revenue.png
│   ├── Top 10 Countries by Revenue Contribution (%).png
│   ├── Top 20 Countries by Average Order Value (AOV).png
│   ├── Customer Cohort Retention (%).png
│   └── Customer Distribution Across RFM Segments.png
│
└── 📄 README.md
```

---

## ❓ Key Business Questions

This project answers the following business questions:

> 1. 📈 How is revenue changing over time?
> 2. 👤 Which customers generate the highest revenue?
> 3. 📦 Which products contribute most to sales?
> 4. 🌍 Which countries are the strongest markets?
> 5. 🔄 Do customers return after their first purchase?
> 6. 🏷️ Which customer segments create the highest business value?
> 7. 💡 What strategies can improve customer retention and revenue?

> 📄 **_For a detailed report, refer to the [Executive Report (PDF)](https://github.com/karandangi123/retail-sales-analytics/blob/main/Executive%20Report.pdf)_**

---

## 📊 Key Findings

### 📅 Monthly Performance


- Revenue showed **seasonal fluctuations** throughout the year.
- Sales **peaked during October and November**, indicating strong holiday-season demand.
- December 2010 revenue dropped significantly because the dataset contains only **partial December data**.
- Average Order Value remained **relatively stable** despite monthly changes in revenue.

---

### 👤 Customer Analysis


- The business serves **4,286 active customers**.
- Customer spending is **highly skewed** — a small percentage of customers generate a disproportionately large share of revenue.
- **Top 10% of customers contribute approximately 60% of total revenue**, highlighting a strong **Pareto (80/20) effect**.

---

### 📦 Product Analysis


- The business sells **4,011 unique products**.
- The highest revenue-generating product is **WHITE HANGING HEART T-LIGHT HOLDER**.
- Only a small percentage of products generate the majority of revenue.
- The **top 10 products contribute 7.28%** of total revenue.

---

### 🌍 Country Analysis


- Customers are distributed across **37 countries**.
- The **United Kingdom dominates** business performance, contributing approximately **84% of total revenue**.
- The **Top 5 countries generate over 95%** of total revenue.
- Countries such as **EIRE, Netherlands, Germany, and France** represent important secondary markets with strong growth potential.

---

### 🔄 Cohort Analysis


- Customer retention **declines noticeably** after the first purchase.
- The **December 2009 cohort** demonstrates the strongest long-term retention because these customers have the longest observation period.
- Several cohorts maintained **relatively higher retention** during the first few months, indicating strong repeat purchase behavior.
- Retention **decreases steadily** over time, highlighting opportunities to improve customer engagement.

---

### 🏷️ RFM Customer Segmentation

Customers were segmented using **Recency**, **Frequency**, and **Monetary Value**.


#### Customer Distribution Across Segments

| Segment | Customers | Share |
|---|---:|---:|
| 🟡 Need Attention | 1,280 | 29.9% |
| 🟢 Champions | 921 | 21.5% |
| 🔵 Potential Loyalists | 656 | 15.3% |
| 🔴 Lost Customers | 636 | 14.8% |
| 🟣 Loyal Customers | 471 | 11.0% |
| 🟠 At Risk | 322 | 7.5% |

> **Key Takeaways:**
> - Nearly **30%** of customers require engagement before becoming inactive.
> - More than **21%** of customers belong to the **Champion** segment and represent the business's most valuable customers.
> - A meaningful portion of customers can be converted into loyal customers through **personalized marketing**.

---

## 💡 Business Recommendations

### 1. 🔁 Improve Customer Retention
Target customers in the **Need Attention** and **At Risk** segments through personalized email campaigns, product recommendations, and limited-time offers to encourage repeat purchases.

### 2. 🏆 Reward High-Value Customers
Retain **Champions** and **Loyal Customers** using loyalty programs, VIP benefits, exclusive discounts, and early access to new products to maximize **Customer Lifetime Value**.

### 3. 📬 Re-engage Lost Customers
Launch **win-back campaigns** using personalized offers, reminder emails, and targeted promotions to recover inactive customers.

### 4. 📊 Optimize Product Strategy
Prioritize inventory planning for **high-performing products** while reviewing low-performing products for possible discontinuation or promotional support.

### 5. 🌐 Expand High-Performing Markets
Increase marketing investment in high-performing countries such as **EIRE, Netherlands, Germany, and France** while maintaining strong market leadership in the **United Kingdom**.

### 6. 🔄 Increase Repeat Purchases
Use insights from **Cohort Analysis** and **RFM segmentation** to improve second-purchase rates through personalized recommendations, cross-selling, and post-purchase engagement.

---

## ✅ Conclusion

This analysis demonstrates how retail transaction data can be transformed into **actionable business insights** through customer analytics, product analysis, cohort analysis, and RFM segmentation. The findings provide clear opportunities to:

- ✅ Improve customer retention
- ✅ Optimize marketing strategies
- ✅ Strengthen inventory planning
- ✅ Increase long-term revenue

By implementing the recommended actions, the business can **enhance customer lifetime value**, **reduce churn**, and **drive sustainable growth**.

---

<p align="center">
  <b>⭐ If you found this project useful, consider giving it a star!</b>
  <br/><br/>
  <i>Prepared by - Karan Dangi</i>
</p>
