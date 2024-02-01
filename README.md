# PRODIGY_ML_02
K-means Clustering Algorithm
## Introduction
<p align='justify'>
K-Means Clustering is an Unsupervised Machine Learning algorithm, which groups the unlabeled dataset into different clusters. Without any previous data training, the machine’s job in this case is to organize unsorted data according to parallels, patterns, and variations.
</p>
## Concept
<p align='justify'>
You are owing a supermarket mall and through membership cards , you have some basic data about your customers like Customer ID, age, gender, annual income and spending score.
Spending Score is something you assign to the customer based on your defined parameters like customer behavior and purchasing data.
</p>
## Problem Statement
<p align='justify'>
You own the mall and want to understand the customers like who can be easily converge [Target Customers] so that the sense can be given to marketing team and plan the strategy accordingly.</p>
## Data Exploration
<p align='justify'>
To form Clusters we extract the relevant features from the dataset Annual Income (k$) and Spending Score (1-100).
StandardSCaler is used to both fit and transform. The fit method is used to compute the mean and std dev for a given feature to be used further for scaling. The transform(data) method is used to perform scaling using mean and std dev calculated using the .fit() method. 
</p>
## KMeans Prediction
<p align='justify'>
Here n_clusters i.e. the number of clusters is determined to 5.
The KMeans algorithm is implemented it takes basic parameters like n_clusters,n_init,random_state.
</p>
## Plotting
<p align='justify'>
Atlast, the plotting is done by means of scatter plot. Then CustomerId and their Cluster number is printed.</p>
