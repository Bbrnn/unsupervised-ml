# CREDIT CARD FRAUD DETECTION USING CLUSTERING
**Objective**

To detect fraudulent transactions and outliers in financial data using unsupervised learning techniques, specifically focusing on clustering and outlier detection methods.

## Dataset
 Credit Card Fraud Detection dataset available on Kaggle. This dataset is ideal because it contains anonymized credit card transactions with features that can be used for both anomaly and outlier detection.

### STEPS INVOLVED
   1. Data exploration and Preprocessing:
        Load and explore the dataset, understanding the distribution of features and the imbalance between fraudulent and non-fraudulent transactions.

        Standardize the data for clustering.
        Use PCA to reduce dimensionality for visualization purposes.

   2. Clustering:
        Apply K-means and DBSCAN clustering algorithms.
        Evaluate the clustering performance using silhouette score and Davies-Bouldin index.

   3. Outlier Detection:
        Z-score Method: Calculate the Z-score for the 'Amount' feature and identify outliers based on a threshold.
        IQR Method: Calculate the interquartile range for the 'Amount' feature and identify outliers that fall outside 1.5 times the IQR.

   4. Visualization:
        Visualize the clusters from K-means and DBSCAN.
        Use box plots and histograms to visualize outliers detected by Z-score and IQR methods.

