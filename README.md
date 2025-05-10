# cryptoclustering
# Crypto Clustering with K-Means and PCA
This project analyzes and groups cryptocurrencies based on price change data using K-Means clustering. It also uses Principal Component Analysis (PCA) to reduce dimensions and improve visualization.

# What This Project Does
Loads and prepares crypto market data from a CSV file

Normalizes the data using StandardScaler

Uses the elbow method to find the best number of clusters (k)

Applies K-Means to group similar cryptocurrencies

Reduces features using PCA

Compares clustering results with and without PCA

Visualizes clusters using hvPlot

# Tools & Libraries
Python

pandas

scikit-learn (KMeans, PCA, StandardScaler)

hvPlot

matplotlib

# Key Visuals
Elbow Curves (before and after PCA)

Cluster scatter plots (original data and PCA-reduced data)

# What We Found
The best value for k = 4 for both original and PCA-reduced data

PCA made the clusters easier to visualize without losing much information

# Files
Crypto_Clustering.ipynb – main notebook with code and visuals

crypto_market_data.csv – input data file

# How to Run
Open the Jupyter Notebook

Run all cells in order

View the plots and answers at the bottom of the notebook









