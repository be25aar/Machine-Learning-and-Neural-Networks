# Machine-Learning-and-Neural-Networks
Customer Segmentation using K-Means and PCA

Project Overview
This project focuses on customer segmentation using **K-Means Clustering** and **Principal Component Analysis (PCA)**. The goal is to identify distinct customer groups based on purchasing behaviour and engagement patterns.
Clustering is performed before and after applying PCA to evaluate the impact of dimensionality reduction on model performance.
Objectives
- Analyse customer data and identify behavioural patterns
- Perform clustering using K-Means algorithm
- Reduce dimensionality using PCA
- Compare clustering performance before and after PCA
- Visualise and interpret customer segments
Dataset
The dataset contains numerical features representing customer behaviour such as spending and engagement.
Preprocessing Steps:
- Selected numerical features
- Removed missing values
- Applied feature scaling (Standard Scaler)
Methodology
1. Feature Scaling
- Standardised data (Mean = 0, Variance = 1)
2. Elbow Method
- Used to determine optimal number of clusters (k = 3)
3. K-Means Clustering (Before PCA)
- Applied clustering on scaled data
- Evaluated using Silhouette Score
4. PCA (Dimensionality Reduction)
- Reduced dataset to 2 principal components
- Retained maximum variance

5. K-Means Clustering (After PCA)
- Applied clustering again with k = 3
- Compared performance

Results
Customer segments identified:
  - Cluster 0: Low-value customers
  - Cluster 1: High-value customers
  - Cluster 2: Moderate customers
PCA improved:
  - Visualisation
  - Noise reduction
  - Interpretability
Visualisations
- Elbow Method Plot
- PCA Explained Variance Plot
- Cluster Scatter Plot (2D)
Business Applications
- Targeted marketing
- Customer retention strategies
- Revenue optimisation
- Data-driven decision making
Advantages
- Simple and efficient clustering
- Improved visualisation using PCA
- Reduced noise and redundancy
Limitations
- Requires predefined number of clusters (k)
- Sensitive to outliers
- Possible information loss due to PCA

Future Work
- Apply DBSCAN or Hierarchical Clustering
- Use more PCA components
- Include categorical features
- Real-time segmentation
Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
Author
Student Name: Benhar Varun Kumar Eguri
Student ID: 24166433 
Module: Machine Learning and Neural Networks
