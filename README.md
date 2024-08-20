# CryptoClustering Market Clustering Analysis

## Project Overview

This project focuses on analyzing and clustering cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA). The goal is to explore how reducing the number of features impacts the clustering results and to visually compare the clusters formed with the original dataset and the PCA-reduced dataset.

## Project Structure

- **Data Source:** The project uses a CSV file (`crypto_market_data.csv`) containing cryptocurrency market data with features such as price change percentages over different time periods.
- **Data Processing:** The data is normalized using `StandardScaler` to ensure that all features contribute equally to the clustering process.
- **Clustering:** K-Means clustering is applied to both the original and PCA-reduced datasets to identify distinct groups within the data.
- **Dimensionality Reduction:** PCA is used to reduce the dataset's dimensionality, focusing on the most significant components.
- **Visualization:** The results are visualized using Elbow curves and scatter plots to compare the clustering outcomes before and after PCA.

## Files and Directories

- **`Resources/crypto_market_data.csv`:** The source file containing the cryptocurrency market data.
- **`Crypto_Clustering_starter_code.ipynb`:** The Jupyter Notebook that contains the entire workflow, including data processing, clustering, and visualization.
- **`README.md`:** This file, providing an overview of the project and instructions for use.

## Requirements

- Python 3.x
- Pandas
- Scikit-learn
- HvPlot
- Matplotlib

You can install the required packages using:

```bash
pip install pandas scikit-learn hvplot matplotlib
