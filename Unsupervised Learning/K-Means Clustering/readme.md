# k-Means Clustering

This notebook explores the implementation and insights derived from k-Means Clustering using the KMeans module from scikit-learn. The primary focus is on demonstrating the functionality of the KMeans algorithm, creating synthetic datasets, and visually inspecting the impact of varying cluster counts on model performance.

## Overview

### Data Creation and Model Training
Utilizing make_blobs from scikit-learn to create synthetic datasets, followed by training the KMeans model with varying numbers of clusters.

### Testing the Model
Assessing the model's performance by visually inspecting decision boundaries and cluster formations for different cluster counts.

### Comparing Results
Examining the impact of assigning different cluster counts and determining the optimal number of centroids using the 'elbow' method based on the model score.

## Key Insights

### Model Training
Demonstrates how KMeans assigns centroids to minimize distances between centroids and data points.

### Visualization
Visual inspection of decision boundaries helps evaluate the clustering effectiveness for different cluster counts.

### Determining Optimal Clusters
Utilizes the 'elbow' method to identify an optimal number of clusters by analyzing the change in scores for varying centroids.

## Observations

- **Impact of Cluster Counts**: Visually comparing clustering results for different cluster counts reveals a point where additional clusters do not significantly improve model performance. This point indicates the optimal number of clusters.

- **Elbow Method**: Plotting scores against centroid counts confirms the diminishing returns beyond a certain number of clusters, aiding in determining the optimal count.

For detailed code implementation and visualizations, refer to the notebook.
