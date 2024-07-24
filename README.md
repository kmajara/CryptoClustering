# CryptoClustering
Using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
Project Overview

This project aims to analyze cryptocurrency data using K-means clustering and Principal Component Analysis (PCA). The goal is to find the optimal number of clusters (k) for both the original data and PCA-transformed data, and to compare the clustering results.
Project Structure

    Resources: Contains the cryptocurrency dataset.
    Crypto_Clustering.ipynb: Contains Jupyter notebook with the code implementation.
    plots and relted analysis are included in the notebook

Data

    Description: The dataset includes cryptocurrency data with features such as price change percentages over different timeframes.

Methodology

    Elbow Method:
        Implement the elbow method to determine the optimal value of k for the original data.
        Plot the inertia values for different k values to visualize the elbow point.
    K-means Clustering (Original Data):
        Apply K-means clustering with the determined optimal k value.
        Visualize the clusters using a scatter plot of price change percentages.
    PCA:
        Perform PCA to reduce the dimensionality of the data.
        Determine the explained variance ratio for each principal component.
    Elbow Method (PCA Data):
        Repeat the elbow method using the PCA-transformed data.
    K-means Clustering (PCA Data):
        Apply K-means clustering to the PCA data with the new optimal k value.
        Visualize the clusters using a scatter plot of the first two principal components.
    Comparison:
        Compare the elbow curves and cluster visualizations from both methods.
        Analyze the impact of using fewer features on the clustering results.

Libraries

    pandas: For data manipulation.
    numpy: For numerical operations.
    sklearn: For machine learning algorithms (K-means, PCA).
    matplotlib/seaborn: For data visualization.
    hvPlot: For interactive visualizations (optional).