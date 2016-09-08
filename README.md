# Constructing Customer Classes/Segments
This project is an analysis of a dataset containing data on various customers' annual spending amounts 
(reported in monetary units) of diverse product categories for internal structure. 
The major goal of this project is to best describe the variation in the different types of customers that a 
wholesale distributor interacts with. Doing so would equip the distributor with insight into how to best 
structure their delivery service to meet the needs of each customer. We can then categorize customers based on their spending habits. Such an insight will be valuable in designing the appropriate A/B tests.

The dataset for this project can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers). For the purposes of this project, the features 'Channel' and 'Region' will be excluded in the analysis — focusing instead on the six product categories recorded for each customer.

The project first goes through a review of unstructured data to understand the patterns and natural categories that the data fits into. 
Then, multiple algorithms are employed to compared and contrast their results. Predictions about the natural 
categories of multiple types in a dataset are also made, and then checked against the results from the unsupervised analysis.

This analysis employs PCA for dimensionality reduction, prior to clustering. The silhouette score is used to determine the number of clusters.

# Tools:
Python, Pandas, sklearn (PCA, GMM, metrics), numpy, matplotlib, seaborn
