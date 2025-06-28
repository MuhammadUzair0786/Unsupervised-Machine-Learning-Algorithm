# Unsupervised-Machine-Learning-Algorithm

# K-Means Clustering

This notebook demonstrates how to use the K-Means clustering algorithm for unsupervised machine learning using Python and scikit-learn.

## What is K-Means Clustering?
- K-Means is an unsupervised learning algorithm used to group data points into a specified number of clusters based on feature similarity.
- It is commonly used for data segmentation, pattern recognition, and exploratory data analysis.

## Steps Covered

- Load and explore the dataset (Iris dataset).
- Visualize the data distribution using pairplots.
- Use the Elbow Method to find the optimal number of clusters by plotting WCSS (Within-Cluster Sum of Squares).
- Apply K-Means clustering to segment the data into clusters.
- Add cluster labels to the dataset.
- Visualize the clustered data using pairplots with predicted cluster labels.
- Compare the clustering results with the original labeled dataset for evaluation.

## Notes

- K-Means requires you to specify the number of clusters (`n_clusters`) in advance.
- The Elbow Method helps determine the best value for `n_clusters`.
- K-Means works best when clusters are spherical and of similar size.

# Hierarchical Clustering and Its Types

This notebook demonstrates how to use Hierarchical Clustering for unsupervised machine learning using Python and scikit-learn.

## What is Hierarchical Clustering?
- Hierarchical Clustering is an unsupervised learning algorithm that builds a hierarchy of clusters.
- It does not require you to specify the number of clusters in advance.
- The results are often visualized using a dendrogram, which shows how clusters are merged or split at each step.

## Types of Hierarchical Clustering

### 1. Agglomerative Clustering (Bottom-Up)
- Starts with each data point as its own cluster.
- At each step, the two closest clusters are merged.
- The process continues until all points are in a single cluster or a stopping criterion is met.
- Most commonly used type in practice.

### 2. Divisive Clustering (Top-Down)
- Starts with all data points in a single cluster.
- At each step, the cluster is split into smaller clusters.
- The process continues until each data point is its own cluster.
- Less commonly used due to higher computational cost.

## Steps Covered

- Load and explore the dataset.
- Compute the distance matrix and plot the dendrogram to visualize the hierarchy.
- Choose the number of clusters by cutting the dendrogram at a chosen level.
- Apply Agglomerative Clustering to assign cluster labels to the data.
- Visualize the clustered data.

## Notes

- Agglomerative clustering is the default and most widely used method.
- Different linkage criteria (single, complete, average, ward) affect how clusters are merged.
- Dendrograms help in deciding the optimal number of clusters.


This notebook is a practical guide for beginners to understand and apply hierarchical clustering and its types for unsupervised data

# DBSCAN Clustering

This notebook demonstrates how to use the **DBSCAN** (Density-Based Spatial Clustering of Applications with Noise) algorithm for unsupervised clustering using Python and scikit-learn.

## What is DBSCAN?
- DBSCAN is a density-based clustering algorithm.
- It groups together points that are closely packed (high density) and marks points that lie alone in low-density regions as outliers (noise).
- Works well for data with clusters of arbitrary shape and is robust to outliers.
- Does not require you to specify the number of clusters in advance.

## Steps Covered

- Generate a non-linearly separable dataset using `make_moons`.
- Visualize the original dataset.
- Apply DBSCAN clustering to the data.
- Assign cluster labels and detect outliers.
- Visualize the clustered data and outliers using scatter plots.

## Notes

- DBSCAN parameters:
  - `eps`: Maximum distance between two samples for them to be considered as in the same neighborhood.
  - `min_samples`: Minimum number of points to form a dense region (cluster).
- Points labeled as `-1` are considered outliers/noise.
- DBSCAN is especially useful for datasets where clusters are not well separated or are of different shapes.

---

This notebook is a practical guide for beginners to understand and apply DBSCAN clustering for unsupervised data analysis and outlier detection.



## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook
- scipy

---

This notebook is a practical guide for beginners to understand and apply K-Means clustering for unsupervised data analysis.