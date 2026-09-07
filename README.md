# Machine Learning Task 2 - Customer Segmentation Using RFM and K-Means

## 📌 Project Overview

This project focuses on **customer segmentation using Machine Learning**.

The notebook uses transaction data to calculate **RFM (Recency, Frequency, Monetary)** values for customers and applies the **K-Means clustering algorithm** to group customers based on their purchasing behavior.

The project includes data cleaning, feature engineering, feature scaling, cluster selection using the Elbow Method, and evaluation using Silhouette Score and Davies-Bouldin Index.

---

## 🎯 Objectives

- Load and inspect the sales transaction dataset.
- Identify and handle missing values.
- Remove cancelled transactions.
- Remove invalid transactions.
- Remove duplicate records.
- Calculate the total transaction amount.
- Perform RFM analysis.
- Scale RFM features.
- Apply K-Means clustering.
- Determine a suitable number of clusters using the Elbow Method.
- Evaluate the clustering results using:
  - Silhouette Score
  - Davies-Bouldin Index
- Visualize customer clusters.

---

## 📂 Dataset

The notebook reads the dataset from:

```text
/content/sales2.xlsx
