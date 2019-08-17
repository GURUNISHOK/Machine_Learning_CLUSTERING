# Machine_Learning_CLUSTERING
CLUSTERING
Finding groups of objects such that the objects in a group will be similar (or related)
to one another and different from (or unrelated to) the objects in other groups.

This clustering mini project contains two clustering techniques that includes Hierarchical CLustering and K Means Clustering.
The project starts by loading the dataset into the jupyter notebook, followed by providing a visual representation of the data set
before performing the clustering technique.


KMEANS:
It is a Partitional clustering approach. 
*Each cluster is associated with a centroid (center point).
*Each point is assigned to the cluster with the closest centroid.
*Number of clusters, K, must be specified. 


HIERARCHICAL:
Produces a set of nested clusters organized as a hierarchical tree. 
Can be visualized as a dendrogram – A tree like diagram that records the sequences of merges or splits.

Then the dataset is all set to explore all the four types of the Hierarchical clustering which includes,

*Single Linkage Hierarchical Clustering:
In single linkage hierarchical clustering, the distance between two clusters is defined as the shortest distance 
between two points in each cluster. For example, the distance between clusters “r” and “s” to the left is equal to the
length of the arrow between their two closest points.



*Complete Linkage Hierarchical CLustering:
In complete linkage hierarchical clustering, the distance between two clusters is defined as the longest distance between 
two points in each cluster. For example, the distance between clusters “r” and “s” to the left is equal to the length of the
arrow between their two furthest points.	


*Average Linkage Hierarchical Clustering:
In average linkage hierarchical clustering, the distance between two clusters is defined as the average distance 
between each point in one cluster to every point in the other cluster. For example, the distance between clusters 
“r” and “s” to the left is equal to the average lengtheach arrow between connecting the points of one cluster to the other.


For all of the above hierarchical clustering their respective scatter plot and their dendrograms were drawn. The
Sum of Squared errors and their Rand Index was obtained.
