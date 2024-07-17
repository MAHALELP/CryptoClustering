# CryptoClustering Project

Welcome to the CryptoClustering project repository! 

This project focuses on clustering cryptocurrencies based on their market data using machine learning techniques like K-means clustering and Principal Component Analysis (PCA).

## Project Overview
The main objective is to analyze how cryptocurrencies perform based on their price change percentages over time. Here’s a breakdown of what we’ve done:

* Data Loading and Preprocessing:
We start by loading the cryptocurrency market data from a CSV file (crypto_market_data.csv).
The data is then standardized to ensure fair comparisons across different features using standard scaling.

* Clustering with K-means:
Using the original scaled data, we determine the optimal number of clusters (k) using the elbow method.
Once k is determined, we apply K-means clustering to group cryptocurrencies based on their price trends.
Visualizations are generated to see how well cryptocurrencies cluster based on their 24-hour and 7-day price change percentages.

* Dimensionality Reduction with PCA:
To simplify our analysis without losing critical information, we use Principal Component Analysis (PCA).
PCA helps us reduce the dimensionality of the data while retaining the most important features.
We again find the best k value using the elbow method on the PCA-transformed data and perform K-means clustering.

* Visualize and Compare Results:
We compare the clustering results obtained from the original data with those from PCA-transformed data.
This comparison helps us understand how using fewer features (through PCA) impacts our clustering outcomes.

## Files Included
* Crypto_Clustering.ipynb: This Jupyter Notebook contains all the Python code used in the project.
* crypto_market_data.csv: The dataset used for analysis, containing cryptocurrency market information.
