## K-Means Clustering 

K_Means Clustering is a broad set of
techniques for finding subgroups
of observations within a data set. This project can be categroized in unsupervised machine learning.

K-Means Clustering Usage
1.Customer Segmentation
2.Fraud Detection
3.Document Classification

The classification of observations into groups requires some methods for computing the distance
or the (dis)similarity between each pair of observations. The result of this computation is known
as a dissimilarity or distance matrix. There are many methods to calculate this distance
information.

The basic idea behind kmeans clustering consists of defining clusters so that the total intra
cluster variation (known as total within cluster variation) is minimized. There are several 
k-means algorithms available. The standard algorithm is the Hartigan Wong algorithm (1979)


Particularly to this project, the main object is to cluster the rating of the movie respected to its genres.

Steps:

1. Data Preparation 

<img src="images/Capture1.JPG"/>


There are two methods used:
1. Gap Statistic 
2. Averaging Method

Through both method, the value of K obtained is 3.

The insight that can be determined is:

Cluster 1 : Film Action has the highest rating and Romcom has the lowest one.
Cluster 2 : Film Comedy has the highest rating and horror has the lowest one
Cluster 3 :The highest rating goes to horror film while Romcom is the lowest.

You can see the repository file on my github: 

k_means_clustering_movie_rating.Rmd  https://github.com/fadhilhilmi/fadhilhilmi.github.io/blob/master/k_means_clustering_movie_rating.Rmd

Dataset can be downloaded on https://github.com/fadhilhilmi/fadhilhilmi.github.io/blob/master/data_cleansing_exercise.rar
