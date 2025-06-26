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

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

---

This notebook is a practical guide for beginners to understand and apply K-Means clustering for unsupervised data analysis.