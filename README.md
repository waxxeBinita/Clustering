#Clustering
For k-means model building, we have used the elbow method to verify the optimal number of clusters. The method provides an elbow-like graph as an output that begins to diminish and lessens gradually as a straight line.
This algorithm was used to track down the optimal value of n which alludes to the centroids of the dataset.
For this model development, we have used the Agglomerative(bottom-up) approach where every observation starts at the bottom-up approach by combining the nearest distance data points together. Using the dataset, we predicted the number of possible clusters in dendrogram.
Like the earlier algorithm, DBSCAN didn’t need to specify the number of clusters earlier. This clustering method is used on a function that calculates the distance between values and the parameters set for closeness as:
·   	The radius of each core(eps) 
·   	the Minimum number of points for each radius to consider the closeness to the core point(min_samples)
·   	Boundary points and Epsilon (radius of circle)
