# Cryptocurrency Clusters
This project uses unsupervised machine learning to cluster cryptocurrency data.

## Description
The purpose of this project was to explore the use of unsupervised machine learning, specifically k-Means, to cluster cryptocurrencies found in a given dataset. It was completed in Jupyter lab using the following languages and libraries:

* Python
* Pandas
* Matplotlib
* Scikit-Learn

The data used was provided by the University of Pennsylvania Data Analysis and Visualization bootcamp.

## Method

First, the data was cleaned and processed to make it usable to for unsupervised learning. This step included tasks like dropping rows with null values, dropping columns not useful for unsupervised learning, and using Get Dummies to convert categorical data to numeric. Due to the use of Get Dummies, it was also necessary to engage in dimensionality reduction first with PCA and then with t-SNE. Next, once the data was prepared it could be plotted as a preview. Then, a for loop provided insight into the best k value to use with k-Means clustering and an elbow curve illustrated this. Finally, the best k value was used with the k-Means unsupervised learning model to cluster the cryptocurrency data. 

## Results

![Image](https://github.com/twolightsabovethesea/cryptocurrency-clusters/blob/main/images/k_means_clusters.png)

A plot of this data revealed that while clustering is possible, other insights would be necessary to offer any meaningful recommendations regarding the desirability of investment in a given cryptocurrency.
