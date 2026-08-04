---

---

## 🎯 3. Task 2 `README.md`
*(Place this inside `oibsip/Task-2-Customer-Segmentation/README.md`)*

```markdown
# Task 2: Customer Segmentation Analysis

## 📌 Project Overview
This project focuses on segmenting customers based on their historical purchasing behavior. Customer segmentation enables businesses to target specific customer groups with tailored marketing strategies.

## 🛠️ Technologies & Tools Used
* **Python**
* **Scikit-Learn** (K-Means Clustering)
* **Pandas & NumPy** (Feature Engineering / RFM)
* **Matplotlib & Seaborn** (Scatter plots & Cluster visualizations)

## 🔍 Methodology
1. **Data Preprocessing:** Standardized transaction data and built RFM (Recency, Frequency, Monetary) metrics.
2. **Feature Scaling:** Applied `StandardScaler` to normalize numeric values for clustering algorithms.
3. **Model Training:** Utilized the **K-Means Clustering** algorithm and determined optimal clusters ($K$) using the Elbow Method.
4. **Segment Profiling:** Grouped customers into distinct categories (e.g., *High-Value Customers*, *Frequent Buyers*, *At-Risk Customers*).

## 💡 Business Recommendations
* **High-Value Customers:** Focus on loyalty rewards and exclusive preview offerings.
* **Occasional Shoppers:** Engage with targeted discount incentives to increase order frequency.

## 🚀 How to Run
```bash
jupyter notebook DataAnalytics_L1_CustomerSegmentation/DataAnalytics_L1_CustomerSegmentation_Task2.ipynb