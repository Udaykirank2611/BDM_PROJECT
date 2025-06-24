# 🛍️ RetailSense: A Data-Driven Approach to Retail Optimization

> A BDM Capstone Project | IIT Madras | 2025  
> Author: Kandagatla Uday Kiran | Roll No: 22f3001962

## 📌 Project Summary

**RetailSense** leverages advanced data analytics to uncover actionable insights for a UK-based e-commerce retailer. The project addresses key business challenges like poor customer retention, high return rates, lack of customer segmentation, ineffective bundling, and unforecasted demand variations using robust analytical methods.

---

## 📦 Dataset

- **Source**: UCI Machine Learning Repository  
- **Link**: [Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Records**: 541,909 transactions  
- **Time Period**: Dec 2010 – Dec 2011  
- **Fields**: `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `UnitPrice`, `InvoiceDate`, `CustomerID`, `Country`

---

## 🧠 Business Problems Solved

1. Classifying customers for targeted marketing (RFM)
2. Analyzing retention over time (Cohort Analysis)
3. Identifying high-return products and customers (Return Analysis)
4. Discovering product bundling opportunities (Apriori Algorithm)
5. Estimating Customer Lifetime Value (CLV) and applying Pareto Principle
6. Analyzing monthly sales trends for inventory planning

---

## 🛠️ Tools & Libraries Used

- **Platform**: Google Colab (Python)
- **Libraries**:
  - `Pandas`, `Numpy` – Data cleaning and feature engineering
  - `Seaborn`, `Matplotlib` – Data visualization
  - `mlxtend` – Apriori algorithm and association rules
  - `Statsmodels` – Time-series analysis
  - `Scikit-learn` – Clustering and model evaluation

---

## 🔍 Analysis Techniques

| Technique | Description |
|----------|-------------|
| **RFM Segmentation** | Classified customers as Champions, Loyal, At-Risk, etc. |
| **Cohort Analysis** | Identified drop in retention after first purchase month |
| **Market Basket Analysis** | Found 2400+ high-confidence item pairings using Apriori |
| **Return Analysis** | Isolated top-returned products and chronic returners |
| **CLV & Pareto Analysis** | 20% of customers & products = ~80% of revenue |
| **Trend Visualization** | Identified Q4 sales peaks and post-holiday return surges |

---

## 📈 Key Findings

- ~1600 “Champion” customers drove the majority of revenue.
- Retention dropped ~70% after first month; urgent need for post-purchase engagement.
- Common bundling items (e.g., cake sets + decorative bags) had 100% confidence and 70× lift.
- Top 5 customers had CLV in millions to billions.
- Returns were concentrated in a few products and individuals.

---

## ✅ Recommendations

- Launch loyalty & win-back programs targeting RFM segments.
- Suggest product bundles at checkout based on Apriori results.
- Improve descriptions for high-return items and restrict frequent returners.
- Focus inventory and marketing on top 20% of revenue-driving SKUs and customers.
- Prepare for Q4 demand spikes in both sales and returns.

---

## 📊 Visuals

Visualizations include:
- RFM score heatmaps
- Cohort retention curves
- Association rules network graphs
- Return losses by customer and product
- Monthly sales and return trends

> 📂 Visuals and code are in the `AnalysisNotebook.ipynb`.

---

## 📚 Theoretical Foundations

- **BDM Concepts Used**:
  - Customer Segmentation & CLV modeling
  - Churn analysis & cohort behavior
  - Market basket theory
  - Pareto efficiency & decision making
  - Data-driven strategy formulation

- **Professional Selling Concepts**:
  - Lifecycle-based targeting (post-purchase)
  - Upselling via bundling
  - Loyalty and retention management

---

## 💬 Contact

**Uday Kiran**  
Email: `udaykirank2611@gmail.com`
IITM BS Program | BDM Capstone Project

---
