# Customer-Segmentation-using-K-means-Clustering
This repository contains a Python implementation of a K-means clustering algorithm designed to group customers of a retail store based on their purchase history. Customer segmentation is a powerful tool for targeted marketing and personalized customer engagement.

Dataset Generation:
A hypothetical customer dataset is generated, including CustomerID, PurchaseAmount, Frequency, and Recency.

Data Preprocessing:
Relevant features (PurchaseAmount, Frequency, Recency) are selected for clustering.
Feature standardization is performed using the StandardScaler to ensure uniform scales for K-means.

Determining Optimal Clusters:
The Elbow method is used to determine the optimal number of clusters (k) based on within-cluster sum of squares (WCSS).

K-means Clustering:
The K-means algorithm is applied with the optimal number of clusters, obtained from the Elbow method.
Customer data is labeled with the assigned cluster.

Cluster Analysis:
The characteristics of each cluster are computed, showing the mean values for PurchaseAmount, Frequency, and Recency.

Visualization:
A scatter plot is created to visualize the clusters based on Purchase Amount and Frequency.

Instructions:
Adjust the optimal_k variable based on the Elbow method plot for the desired number of clusters.
Run the script to perform K-means clustering and visualize the results.
