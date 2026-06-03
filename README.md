# 🛒 Customer Segmentation using K-Means & RFM Analysis

## 📌 Project Overview

Developed an end-to-end customer segmentation solution using RFM (Recency, Frequency, Monetary) analysis and unsupervised machine learning to identify distinct customer groups and generate actionable business strategies.

**Dataset:** UCI Online Retail Dataset

- 541,909 transactions processed
- 4,338 unique customers analyzed
- UK-based retail transactions (2010–2011)

---

## 🎯 Business Objective

Identify high-value and at-risk customers to support:

- Customer retention strategies
- Targeted marketing campaigns
- Revenue optimization
- Customer lifetime value improvement

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## 📊 Feature Engineering

Built customer-level features including:

- Recency
- Frequency
- Monetary Value
- Average Basket Value
- Unique Products Purchased
- Weekend Purchase Ratio
- Returns Ratio

Applied:

- Log Transformation
- Robust Scaling
- Outlier Treatment

---

## 🤖 Clustering Models Evaluated

| Model | Silhouette Score | Davies-Bouldin | Calinski-Harabasz |
|---------|---------|---------|---------|
| K-Means | 0.381 | 1.092 | 3189.7 |
| Hierarchical | 0.301 | 1.252 | 2882.8 |
| DBSCAN | 0.513 | 1.404 | 1597.4 |
| GMM | 0.231 | 1.444 | 1730.9 |

**Selected Model:** K-Means (k=4)

Chosen for its strong cluster separation and business interpretability.

---

## 👥 Customer Segments Identified

### 🏆 Champions
- 21.4% of customers
- Generated 67% of total revenue
- Highest purchase frequency and spending

### 🔄 Regulars
- Consistent purchasing behavior
- Strong cross-sell and upsell opportunities

### ⚠️ At-Risk
- Previously active customers with declining engagement
- Suitable for win-back campaigns

### 📉 Low Engagement
- Largest customer group
- Low spending and purchase frequency
- Opportunity for activation campaigns

---

## 💡 Key Business Insights

- 21% of customers generated 67% of revenue, highlighting a strong VIP customer segment.
- More than half of customers belonged to the Low-Engagement segment, representing significant growth potential.
- At-Risk customers showed early signs of churn and should be targeted with retention campaigns.
- Regular customers displayed high basket values, indicating opportunities for increased purchase frequency.

---

## 📈 Business Recommendations

1. Launch VIP retention programs for Champions.
2. Implement win-back campaigns for At-Risk customers.
3. Create activation campaigns for Low-Engagement customers.
4. Increase cross-selling and upselling for Regular customers.
5. Monitor customer segment migration monthly.

---

## 📁 Deliverables

- Customer Segmentation Notebook
- Executive Business Report
- Customer Segment Dataset (`customer_segments_final.csv`)

---

## 🚀 Project Outcome

Successfully transformed raw transaction data into actionable customer intelligence, enabling data-driven marketing, customer retention, and revenue growth strategies through machine learning-based segmentation.
