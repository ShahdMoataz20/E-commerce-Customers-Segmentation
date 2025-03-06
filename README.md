# 🛍️E-commerce Customer Segmentation – MLSC Data Science Graduation Project
******📌 Project Overview:******

This project focuses on customer segmentation for an e-commerce platform using unsupervised machine learning. The goal is to analyze customer behavior, group them into meaningful segments, and provide recommendations for coupon distribution to enhance customer loyalty and satisfaction.

The dataset consists of customer demographics, transaction history, city and gender information, and coupon usage data. We employ clustering techniques to identify customer segments and derive actionable insights for business decision-making.

******🚀 Key Objectives******

1. Feature Engineering: Extract key attributes like customer demographics(e.g., gender, city) and transactional behavior (e.g., coupon usage frequency, transaction status).
2. Clustering Models: Train and evaluate an unsupervised machine learning model (K-Means) for customer segmentation.Ensure to explore different numbers of segments (clusters) and optimize my model for meaningful customer groups.
3. Evaluation: Use Silhouette Score, Inertia, and visualization techniques to determine the best clustering approach.
4. Insights & Recommendations: Analyze segments and suggest strategies for coupon allocation to maximize customer retention.

******📊 Dataset Description******

The dataset consists of five tables:

* Customers: Contains customer_id, join_date, city_id, and gender_id.
* Genders: Maps gender_id to gender names.
* Cities: Maps city_id to city names.
* Transactions: Includes transaction_id, customer_id, transaction_date, transaction_status, coupon_name, burn_date, and branch_id.
* Branches & Merchants: Provide branch and merchant details.

******🏆 Methodology******

  1️⃣ Data Preprocessing: 
  * Merged datasets to integrate demographic and transactional data.
  * Handled missing values, outliers, and transformed categorical variables.
  * Scaled numerical features for clustering.

  2️⃣ Feature Engineering:
  * Derived transaction frequency, recency, and coupon usage rates.
  * Used city_id and gender_id as categorical identifiers.

  3️⃣ Clustering Techniques:
  * K-Means Clustering (optimized using the Elbow Method & Silhouette Score).
  * Finding the best 'k' using Elbow method is 6 with Silhouette Score: 0.40146108955786375

  4️⃣ Evaluation Metrics:
  * Silhouette Score: Measures the compactness and separation of clusters.
  * Inertia: Used to determine the optimal number of clusters for K-Means.
  * Cluster Visualizations: Box plots, and distribution analysis.


******🔍 Key Findings & Insights******

* Customers were grouped into 6 distinct clusters based on their transaction behavior.
* High-value, frequent shoppers were identified as the most loyal segment.
* Less frequent shoppers showed potential for engagement through targeted promotions.
* Certain cities and customer demographics showed a higher coupon redemption rate.


******🎯 Recommendations for Coupon Strategy******

* High-value customers (Clusters 3 & 4): Reward loyalty with premium offers.
* Moderate customers (Clusters 0 & 5): Provide moderate discounts to keep them engaged.
* Low-value customers (Clusters 1 & 2): Use aggressive discounts to boost retention.


******📈 Visualizations******

The project includes line chart while using elboww method to show the best k.

![image](https://github.com/user-attachments/assets/d3cb1d72-b640-40e9-87d3-ee11e9f0beae)

The project includes box plots to analyze customer segments.

![image](https://github.com/user-attachments/assets/af527ecf-f505-4156-a507-a63fd5534993)















