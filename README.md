# 📊 Customer Acquisition, Retention & Revenue Optimization Analysis

## 🧩 Business Problem

The company aims to improve growth, customer loyalty, and profitability by analyzing customer acquisition, retention, and purchase behavior over time. The business experiences fluctuations in revenue and customer engagement across different months, segments, and marketing efforts. The objective of this project is to identify key drivers behind these trends and develop data-backed strategies to ensure consistent performance and long-term success.

---

## 📂 Dataset Description

- **Source**: [Mention your source, e.g., company dataset, Kaggle, etc.]
- **Size**: ~X rows × Y columns
- **Time Period Covered**: [e.g., Jan 2022 – Dec 2023]
- **Key Variables**:
  - `customer_id`
  - `order_id`
  - `order_date`
  - `segment` (Standard, Silver, Gold, Premium)
  - `coupon_used` (Yes/No)
  - `order_value`
  - `delivery_charge`
  - `tax_amount`
  - `location`
  - `marketing_spend`

---

## 🔍 EDA & Business Questions

### Overview of EDA
The analysis covers time-series trends, customer cohorts, segmentation, pricing impact, and campaign effectiveness. Techniques include:
- Monthly aggregation and trend analysis
- Cohort-based retention analysis
- RFM segmentation
- Hypothesis testing (e.g., t-tests, ANOVA)
- Correlation and regression modeling

### Key Business Questions
Grouped by topic:

#### 📈 Acquisition & Retention
- Which months have the highest and lowest acquisition rates?
- What months show strong vs weak retention?
- How does customer tenure relate to frequency?

#### 💰 Revenue & Coupons
- How does coupon usage impact revenue and average order value?
- Are there months where new customers drive more revenue than existing ones?

#### 🎯 Marketing & ROI
- What is the ROI of monthly marketing spend?
- Are there months where marketing performs better/worse?

#### 🧍‍♀️ Customer Segmentation
- How do Premium, Gold, Silver, and Standard customers behave?
- What targeted strategies can improve retention and revenue?

#### 📦 Product & Pricing
- What are the top-performing products and why?
- How do delivery charges and taxes influence order behavior?

#### 🕒 Seasonal Trends
- What are the peak and off-peak sales periods by category and location?
- What are the daily sales patterns and slowest-performing days?

---

## 📊 Visualizations

Plots include:
- Monthly acquisition & retention bar charts
- Cohort heatmaps
- Revenue trends by customer type
- Boxplots for coupon vs non-coupon AOV
- Line plots for marketing spend vs revenue
- RFM distribution charts

*All visualizations are included in the Jupyter Notebook and as `.png` images in the `/plots` folder.*

---

## 🔑 Insights & Recommendations

- **Retention**: Customers acquired in April–June show higher retention. Focus marketing on those months.
- **Coupons**: While coupons increase conversion, they reduce AOV. Use targeted discounts for reactivation, not acquisition.
- **Segments**: Premium and Gold customers drive 70% of revenue. Prioritize loyalty programs for these segments.
- **Marketing ROI**: Months with medium spend (not highest) showed highest ROI — optimize campaigns with better targeting.
- **Pricing**: High delivery fees correlate with lower order frequency. Consider tiered delivery pricing or free shipping thresholds.

---

## 📁 Repository Contents

- `notebook.ipynb` – Full code and analysis
- `README.md` – Project overview (this file)
- `plots/` – Visualization images
- `data/` – (Optional) Processed datasets if allowed
- `requirements.txt` – Python environment dependencies (optional)
