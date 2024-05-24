# CryptoClustering
# Overview
This project focuses on the analysis and clustering of cryptocurrency data utilizing unsupervised learning techniques, specifically K-Means clustering, both with and without the application of optimization techniques such as Principal Component Analysis (PCA).

# Results
The analysis involved the following key steps:

- Data Preprocessing: Loading and examining the cryptocurrency market data.
- Normalization: Scaling the data using StandardScaler.
- Cluster Analysis:
      -Applying K-Means clustering to the original scaled data to determine the optimal number of clusters (k).
      -Employing PCA to reduce dimensionality and then applying K-Means clustering to find the optimal k.
-Visualization and Comparison:
      -Comparing the clusters derived from the original scaled data with those from the PCA-transformed data.
      -Comparing the Elbow curves from both datasets.

# Conclusion
The analysis highlights the benefits of using optimization techniques like PCA to enhance clustering results. PCA reduces the dimensionality of the data, allowing for more accurate identification of significant patterns and clusters.
