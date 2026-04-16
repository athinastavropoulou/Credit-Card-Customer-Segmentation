# Strategic Customer Segmentation: Credit Card Portfolio Analysis 💳📊

## Project Overview
This project focuses on **Unsupervised Machine Learning** to perform customer segmentation for a credit card dataset. By identifying distinct groups of customers based on their spending habits and credit profiles, businesses can tailor marketing strategies and improve customer retention.

## Technical Workflow
1. **Data Preprocessing & Scaling:** Standardized features using `StandardScaler` to ensure all metrics (credit limits, total cards, visits) contribute equally to the distance-based algorithms.
2. **Dimensionality Reduction:** Applied **PCA (Principal Component Analysis)** to reduce data complexity and visualize clusters in a 2D space.
3. **Multi-Algorithm Comparison:** Implemented and evaluated 4 different clustering techniques:
    * **K-Means**
    * **Agglomerative Clustering**
    * **DBSCAN**
    * **Gaussian Mixture Models**
4. **Performance Evaluation:** Used the **Silhouette Score** as the primary metric to determine the optimal number of clusters and the most effective algorithm.

## Key Technical Skills
* **Clustering Algorithms:** K-Means, DBSCAN, Hierarchical Clustering.
* **Feature Engineering:** PCA, Standardization.
* **Evaluation Metrics:** Silhouette Score, Elbow Method.
* **Visualization:** Seaborn Heatmaps, PCA Scatter Plots.

## Tech Stack
* Python (Pandas, Scikit-learn, Matplotlib, Seaborn).
