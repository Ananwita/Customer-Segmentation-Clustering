# Customer Segmentation using Clustering Algorithms

## Problem Statement:
Group customers into meaningful segments based on their spending behavior and income level.

## Objective:
Help businesses understand customer types (e.g., "budgef", "premium", "moderate") to personalize marketing.

## Dataset
Mall Customers Dataset  
Contains 200 customer records with the following features:
- Age
- Annual Income (k$)
- Spending Score (1–100)

## Algorithms Used
1. K-Means Clustering
2. Hierarchical Clustering
3. DBSCAN (Density-Based Clustering)

## Methodology
- Data preprocessing and feature selection
- Feature scaling using StandardScaler
- Elbow method to determine optimal clusters
- Cluster visualization and interpretation
- Algorithm comparison

## Key Results
- Optimal number of clusters (K-Means): 4
- Identified distinct customer segments such as:
  - Premium Customers
  - Conservative Customers
  - Young Active Customers
  - Careful High-Income Customers
- Hierarchical clustering supported the K-Means result.
- DBSCAN identified density-based clusters and noise points.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- SciPy

## Conclusion
K-Means clustering provided the most interpretable segmentation for this dataset. The analysis demonstrates how clustering techniques can help businesses understand customer behavior and design targeted marketing strategies.
