# Cryptocurrency Clustering Analysis

## Overview

This project demonstrates the application of K-Means clustering on a dataset containing cryptocurrency market data. The primary goal is to group cryptocurrencies based on similar features, helping identify patterns in the market.

The analysis involves:
1. Preprocessing and scaling the data.
2. Finding the optimal number of clusters (k) using the Elbow method.
3. Applying K-Means clustering with the original data.
4. Reducing dimensionality with Principal Component Analysis (PCA).
5. Reapplying K-Means clustering with the reduced data.
6. Comparing the results of clustering with and without PCA.

## Project Files

- **crypto_clustering_notebook.ipynb**: The main Jupyter Notebook containing all code and analysis steps.
- **Resources/crypto_market_data.csv**: The dataset used for analysis.
- **README.md**: Documentation and project overview.

## Dependencies

The project requires the following Python libraries:
- pandas
- hvplot
- scikit-learn

You can install the necessary libraries using pip:
```bash
pip install pandas hvplot scikit-learn
