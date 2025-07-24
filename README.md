# 🧠 Customer Clustering with K-Means

This project demonstrates how to segment customers using unsupervised machine learning techniques, specifically **K-Means Clustering**, based on key behavioral metrics. 
The goal is to help businesses better understand their customer base for targeted marketing, retention, and service optimization.

🧩 Problem Statement
Businesses often struggle to segment their customers effectively. This notebook solves that problem by:

- Extracting meaningful features such as Recency, Frequency, and Monetary Value (RFM).
- Applying K-Means Clustering to discover natural groupings.
- Visualizing the results for actionable insights.


📊 Features Used for Clustering

- Recency: Days since last purchase
- Frequency: Number of purchases
- Monetary: Total amount spent
  
** These features are normalized


📌 Key Steps in the Notebook

1- Data Loading & Cleaning
filters out anomalies & and nan customer ID Values.

2- Apply EDA
perform exploratory data analysis on the filtered data.

3- RFM Feature Engineering
Constructs key behavioral metrics from transactional data.

4- Feature Scaling & Optional PCA (no PCA applied in the notebook)
Ensures fair clustering and optional dimensionality reduction.

5- Optimal Cluster Selection
Uses Elbow Method to identify optimal number of clusters

6- K-Means Clustering
Applies algorithm and assigns customers to clusters.

7- Visualization & Interpretation
Uses 2D plots and descriptive stats to understand each cluster.

📈 Sample Output

<img width="1070" height="701" alt="output" src="https://github.com/user-attachments/assets/b425b38f-a547-4181-b962-0a956dabcd1d" />
