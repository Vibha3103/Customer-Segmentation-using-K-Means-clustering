#  Customer Segmentation using K-Means Clustering

##  Project Overview

This project focuses on grouping customers into different segments based on their purchasing behavior using the K-Means Clustering algorithm. The goal is to help businesses understand customer patterns and improve marketing strategies.

---

## Objective

* Group customers based on similar characteristics
* Identify different types of customers
* Improve targeted marketing strategies
* Increase business sales and customer satisfaction

---

## Problem Statement

Businesses often treat all customers the same, which leads to:

* Inefficient marketing
* Poor customer targeting
* Loss of potential high-value customers

This project solves the problem by segmenting customers into meaningful groups.

---

## Features

* Data preprocessing and cleaning
* Feature selection (Income, Spending Score, Age)
* Elbow Method to find optimal clusters
* K-Means clustering implementation
* Advanced visualization with labeled clusters
* PCA-based visualization
* Business insights for each segment

---

## Dataset Description

The dataset includes:

* Customer_ID – Unique ID
* Gender – Male/Female
* Age – Customer age
* Annual Income (k$) – Income level
* Spending Score (1–100) – Customer spending behavior

---

## Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

##  Methodology

1. Data Collection from dataset (CSV file)
2. Data Preprocessing (handling missing values, encoding Gender)
3. Feature Selection (Income, Spending Score, Age)
4. Finding optimal clusters using Elbow Method
5. Applying K-Means Clustering
6. Assigning cluster labels to customers
7. Visualization of clusters using graphs
8. PCA for dimensionality reduction
9. Analysis and interpretation of clusters

---

## Visualization Outputs

* Elbow Curve (WCSS vs Number of Clusters)
* Cluster Scatter Plot (Income vs Spending Score)
* PCA Cluster Visualization
* Cluster Distribution Graph

---

## Customer Segments (Example)

* **Premium Customers** – High income, high spending
* **Budget Customers** – Low income, low spending
* **Target Customers** – High income, low spending
* **Average Customers** – Moderate income and spending

---

##  How to Run the Project

1. Upload dataset in Google Colab or Jupyter Notebook
2. Run all cells step-by-step
3. View cluster outputs and visualizations
4. Analyze customer segments

---

##  Expected Output

* Customers grouped into clusters
* Graphical representation of segments
* Business insights for marketing strategies

---

##  Advantages

* Better understanding of customers
* Helps in targeted marketing
* Improves customer retention
* Increases business efficiency

---

##  Limitations

* Requires proper selection of number of clusters (K)
* Sensitive to outliers
* Results depend on data quality

---

##  Future Enhancements

* Use advanced clustering (DBSCAN, Hierarchical)
* Real-time customer segmentation
* Integration with CRM systems
* AI-based recommendation systems

---

##  Author

Vibha Shanbhag

---

##  Conclusion

This project demonstrates how clustering techniques like K-Means can be used to segment customers effectively, helping businesses make better data-driven decisions and improve overall performance.

---
