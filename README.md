# Module 18 | Challenge - Cryptocurrencies
Using Python, Jupyter Notebook, and Supervised Machine Learning

## Background and Overview

Using unsupervised machine learning we will look at the world of Cryptocurrencies for tradable coins and reduce the dimension of the dataset.
All data was cleaned and the dimension reduce to produce a list of cryptocurrencies that are trading how they can be grouped to create a classification system for in investment. Because is it unsupervised machine learning we will NOT be training our data.
We will apply 4 different processes to the data.

# Preprocessing the Data for PCA
# Reduce the Data Dimension Using PCA
# Clustering Cryptocurrencies Using K-means
# Visualizing Cryptocurrencies Results

## Deliverable 1: Preprocessing the Data for PCA

Cleaning the dataframe for PCA

![D1](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D1.png)

## Deliverable 2: Reducing Data Dimensions Using PCA

Using PCA we reduce the dimension to three components: PC 1, PC 2, and PC 3.

![D2](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D2.png)

## Deliverable 3: Clustering Using K-Means

Using the Elbow Curve method we found and used a K value of 4. A value of 4 provided the best inertia reading according to the graph.

![D3](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D3.png)

We also generated a new DataFrame that included predicted clusters and cryptocurrencies features.

![D3-B](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D3-B.png)


## Deliverabel 4: Visualizing Cryptocurrencies

We visualize our results using a 3D-Scatter with the PCA data and the clusters.

![D4](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D4.png)


To help visualize the complexity of cryptocurrencies market we visualize the TotalCoinsMined vs TotalCoinSupply.

![D4-B](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D4-B.png)


## Summary
The cryptocurrencies market is large and evolving. Although the number of cryptocurrencies continue to grow by the minute not all products are tradable or suitable for the trading market. Using unsupervised machine learning we are able to delivery a table with over 500 tradable cryptocurrencies that for the investment banking team to review for a tradable product.

![D4-C](https://github.com/JimmyJ-D/Cryptocurrencies/blob/main/Resources/D4-C.png)
