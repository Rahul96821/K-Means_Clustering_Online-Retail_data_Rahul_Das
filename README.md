Customer Segmentation using RFM & Clustering


📌 Project Overview

This project applies RFM (Recency, Frequency, Monetary) analysis and clustering techniques to segment customers from an online retail dataset. The goal is to identify different customer groups and provide actionable insights for marketing strategies, retention, and revenue growth.

📂 Dataset

The dataset is an Online Retail transactional dataset containing customer purchase behavior.

CustomerID – Unique identifier for each customer

InvoiceDate – Date of purchase

InvoiceNo – Transaction number

Quantity, UnitPrice – Order details

Country – Customer’s country

From this, the following RFM features were derived:

Recency (R): How recently a customer made a purchase

Frequency (F): How often a customer makes purchases

Monetary (M): Total spending of the customer

⚙️ Methodology

Data Cleaning & Preprocessing

Handled missing values

Removed outliers (IQR method)

Computed RFM metrics

Standardized features using StandardScaler

Clustering Models

K-Means clustering (with Elbow & Silhouette methods to determine optimal clusters)

Hierarchical clustering (visualized using dendrograms)

Cluster Evaluation

Optimal number of clusters: 3

Visualized results using boxplots for RFM distributions across clusters

📊 Results & Insights

Cluster 0: Low spenders, low frequency, high recency → Inactive/low-value customers

Cluster 1: Medium spenders, moderate frequency → Potential/regular customers

Cluster 2: High spenders, frequent buyers, recent activity → Loyal & high-value customers

🎯 Business Applications

Cluster 0: Re-engagement campaigns (discounts, reminders)

Cluster 1: Loyalty programs & cross-selling

Cluster 2: VIP services & exclusive offers to retain high-value customers

🛠️ Tech Stack

Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

🚀 Conclusion

This project demonstrates how RFM analysis combined with clustering can help businesses:

Understand customer behavior

Create personalized marketing campaigns

Improve customer retention & revenue
