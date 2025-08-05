# 📊 Product Sales Analysis Report

This report presents insights from the analysis of a 15,000-row product sales dataset, focusing on sales performance across three methods — Email, Call, and Email + Call — over a 6-week period. It includes data validation, key visual findings, a custom performance metric, and actionable business recommendations.

---

## ✅ Data Validation Summary

Each column in the dataset was examined and cleaned to ensure data quality:

- **Week**: Verified as integer values between 1–6.
- **Sales Method**: Standardized all naming inconsistencies to ensure only three categories exist: "Email", "Call", and "Email + Call".
- **Customer ID**: Confirmed uniqueness and proper format.
- **Number Sold**: Checked for positive integers; no anomalies.
- **Revenue**: Missing values (~7%) were filled using average revenue per sales method.
- **Years as Customer**: Any values exceeding 41 were capped, reflecting the company’s 1984 founding date.
- **Site Visits**: Confirmed all values fall within expected behavior.
- **State**: All 50 U.S. states were represented and valid.

---

## 📊 Exploratory Analysis

### Single-Variable Insights

- **Revenue Distribution**: Skewed toward lower values, but some methods produce significantly higher returns.
- **Customer Count by Sales Method**: The majority of customers engaged via Email, followed by Call and Email + Call.

### Relationship Insights

- **Revenue Over Time by Method**: Email started strong but declined weekly. Email + Call demonstrated a consistent upward trend, indicating growing effectiveness. The Call method showed early gains but diminished over time.

- **Customer Tenure & Engagement**: Customers using Email + Call showed higher years of loyalty and made more site visits, suggesting deeper engagement.

---

## 📐 Custom Business Metric: ARCPSE

To compare the effectiveness of each sales method, we defined a new performance metric:

**Average Revenue per Customer Sales Effort (ARCPSE)**  
This adjusts total revenue by the estimated effort required per customer for each method.

| Sales Method    | Effort Weight | ARCPSE ($) |
|-----------------|----------------|------------|
| Email           | 0.5            | 194.26     |
| Email + Call    | 1.0            | 183.65     |
| Call            | 3.0            | 15.87      |

> While Email shows the highest efficiency, Email + Call strikes the best balance between growth and customer engagement.

---

## 💡 Business Recommendations

1. **Invest in the Email + Call Strategy**  
   It produces steady revenue growth, deeper customer engagement, and a strong return on effort.

2. **Limit Resources on Call-Only Approach**  
   Despite initial returns, it is the least efficient method with the lowest ARCPSE and declining trend.

3. **Use Email for Scalable Outreach**  
   Best suited for automated, low-cost campaigns, especially early in the sales cycle.

4. **Monitor ARCPSE Weekly**  
   Use this metric as a dashboard KPI to guide strategy and optimize resource allocation across methods.

---

## 📬 Final Summary

Our analysis shows that while each method has strengths, the **Email + Call** strategy offers the most reliable path to sustainable revenue and long-term customer engagement. With strong data validation, custom metrics, and targeted visualization, this report guides future sales efforts with evidence-backed clarity.
