Data Preprocessing:

    Standardization: Scaling features to have zero mean and unit variance ensures that all features contribute equally to the clustering algorithms.
    PCA for Visualization: PCA reduces the dataset's dimensionality to two components for easy visualization, though the clustering itself is performed on the full feature set.

Clustering:

    K-means: This algorithm partitions the data into clusters based on the mean of the data points, adjusting for the chosen number of clusters.
    DBSCAN: Density-based clustering that identifies clusters based on density and marks low-density points as outliers.

Outlier Detection:

    Z-score Method: Identifies outliers by measuring how many standard deviations away a point is from the mean.
    IQR Method: Uses the interquartile range to determine outliers, marking points outside 1.5 times the IQR as outliers.

Evaluation and Visualization:

    Silhouette Score and Davies-Bouldin Index: Metrics to evaluate clustering performance, with higher silhouette scores and lower Davies-Bouldin indices indicating better-defined clusters.
    Visualization: Scatter plots of clusters and box plots/histograms of outliers help visually interpret the results.