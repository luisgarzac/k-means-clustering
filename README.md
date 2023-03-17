# **K-means clustering**

We applied the k-means algorithm to a series of datasets using dendrograms, elbow method, silhouette score, and scikit-learn.





> Code T6-1 : We worked with the 'movies' dataset creating a hierarchical dendrogram.


> Code T6-2 : Taking advantage of the scipy.cluster.hierarchy and numpy libraries, we created a dendrogram for hierarchical clustering, which we modified several times by implementing the elbow method to find the optimal number of clusters 'k'.

> Code T6-3: We created a dataset using numpy by utilizing the random.random class, and used the scipy library to import k-means for implementation on the dataset.

> Code T6-4: From the 'wine' dataset, we specifically worked with 'winequality-red', which we normalized and implemented scikit-learn's AgglomerativeClustering to visualize the histogram of the clusters and later create a dendrogram of the wines. We also applied k-means using the scikit-learn library. 

> Code T6-5: We utilized the scikit-learn and scipy libraries to implement the elbow method and silhouette score for clustering.

> Code T6-6: We used the 'make_blobs' dataset from the scikit-learn library to calculate affinity propagation using the following tool from scikit-learn: from sklearn.cluster import AffinityPropagation.

> Code T6-7: We worked with ring-shaped distributions, applying different algorithms such as k-means, k-medoids, and spectral clustering, which yielded the best results.



## **Datasets**
*   make_blobs
*   wine
*   movies

