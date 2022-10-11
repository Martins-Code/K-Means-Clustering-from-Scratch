# K-Means-Clustering-from-Scratch

Project Overview
We'll create a k-means clustering method from scratch in this project. An unsupervised machine learning method called clustering can detect patterns in your data. One of the most common types of clustering is K-means.
We'll create our algorithm using python and pandas. We'll then compare it to the reference implementation from scikit-learn.

Project Steps

1. Write out pseudocode for the algorithm
2. Code the k-means algorithm
3. Plot the clusters from the algorithm
4. Compare performance to the scikit-learn algorithm
 
 
K-means overview
We can cluster data points using the unsupervised machine learning technique known as K-means. This makes it possible for us to identify trends in the data that will aid in a more thorough analysis. Since K-means is an iterative method, it will eventually converge to the best clustering.

To run a k-means clustering:

1. Specify the number of clusters you want (usually referred to as k).
2. Randomly initialize the centroid for each cluster. The centroid is the data point that is in the center of the cluster.
3. Determine which data points belong to which cluster by finding the closest centroid to each data point.
4. Update the centroids based on the geometric mean of all the data points in the cluster.
5. Run 3 and 4 until the centroids stop changing. Each run is referred to as an iteration.
