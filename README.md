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


1. **Load Dataset**  
   Import the `sales2.xlsx` dataset using Pandas.

2. **Explore Data**  
   Use `head()` and `info()` to understand the dataset.

3. **Check Missing Values**  
   Identify missing values using `df.isnull().sum()`.

4. **Clean Data**  
   Remove missing Customer IDs, cancelled invoices, invalid transactions, and duplicates.

5. **Create Total Amount**  
   Calculate transaction value using:
   `TotalAmount = Quantity × Price`

6. **Perform RFM Analysis**  
   Calculate:
   - Recency
   - Frequency
   - Monetary

7. **Scale Features**  
   Standardize RFM features using `StandardScaler`.

8. **Apply K-Means**  
   Use the Elbow Method and apply K-Means clustering with **2 clusters**.

9. **Evaluate & Visualize**  
   Evaluate clusters using Silhouette Score and Davies-Bouldin Index and visualize the customer clusters.

10. **Interpret Results**  
    Analyze the cluster characteristics to understand different customer purchasing behaviors.

## Results

- **Clusters:** 2
- **Silhouette Score:** 0.9314175603189809
- **Davies-Bouldin Index:** 0.5834201660128137

## Technologies

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab
- Excel

## Project

**Customer Segmentation Using RFM Analysis and K-Means Clustering**

```text
/content/sales2.xlsx
