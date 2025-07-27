# 🛍️ RFM Customer Segmentation with Online Retail Dataset
This project performs Recency-Frequency-Monetary (RFM) analysis on a large online retail dataset from Kaggle/UCI to better understand customer purchase behavior and segment customers for targeted marketing.

The dataset contains over 500,000 transaction records from a UK-based online retailer between 2009 and 2011.

## 📊 RFM Analysis & Scoring
For each customer, I calculated:

- ⏰ Recency – How recently the customer made a purchase

- 🔄 Frequency – How often the customer made purchases

- 💰 Monetary – How much total money the customer spent

Customers were scored on a 1–5 scale using quantiles, with higher scores indicating more valuable customers (e.g., recent, frequent, high spenders). These scores were combined into RFM segments.

## 🛒 Customer Segmentation
Based on RFM scores, customers were grouped into segments:

## Segment	Description
- 🥇 Champions	Recent, frequent, and high-spending customers
- 🎯 Loyal Customers	Repeat buyers with strong spending
- 🔎 Potential Loyalists	New customers with promising behavior
- ⚠️ At Risk	Previously active customers now inactive
- ❌ Lost	Inactive customers with minimal value

These groups help businesses create targeted marketing strategies such as loyalty rewards for champions and win-back campaigns for at-risk customers.

## 📉 Visualizations
Used Matplotlib and Seaborn to create:

📈 Heatmaps showing average R, F, M scores by segment

## 🎯 Key Outcomes
- Cleaned and processed over 500,000 transaction records

- Calculated total spend and RFM metrics per customer

- Assigned quantile-based RFM scores for segmentation

- Grouped customers into actionable marketing segments

- Visualized segment profiles and distributions

## 🛠️ Technologies Used
- Python

- Pandas – data manipulation

- Matplotlib – data visualization

- Seaborn – heatmaps and charts

- Jupyter Notebook – analysis environment

## 👨‍💻 Author

**Syed Danish Ahmed**

**Aspiring Data Scientist | Computer Engineering Student**

If you found this project useful, please ⭐ the repo. Your support is appreciated!

Dataset Source: Kaggle - https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset
