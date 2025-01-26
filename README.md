# Airlines-Customer-Clustering-Analysis
This repository contains a project for performing customer segmentation on airline data using clustering algorithms. The project applies different machine learning techniques such as KMeans, Agglomerative Clustering, DBSCAN, and Hierarchical Clustering to segment customers based on their travel behavior and other related features.

# Overview
he dataset contains customer details and their activities, including miles traveled, credit card usage, flight transactions, and more. The goal of the project is to segment customers into distinct clusters to better understand their behavior.
# Airline Customer Segmentation Using Clustering

This repository contains a project focused on performing customer segmentation on airline data using clustering algorithms. The project applies different machine learning techniques such as KMeans, Agglomerative Clustering, DBSCAN, and Hierarchical Clustering to segment customers based on their travel behavior and other related features.

## Key Steps in the Project

### 1. Data Loading and Preprocessing

- **Load the data and perform initial data exploration**: Load the dataset and examine its structure and content.
- **Rename columns for better understanding and clean up data**: Rename columns for clarity and remove unnecessary columns.
- **Handle missing values**: Ensure that there are no missing values in the dataset (this dataset does not contain missing values).

### 2. Exploratory Data Analysis (EDA)

- **Visualizations using heatmaps, boxplots, and bar plots**: Perform visual analysis to understand the distribution and correlation of the data.
- **Analyzing the relationship between different variables**: Use correlation analysis and visualizations to examine relationships between features.

### 3. Clustering Algorithms

#### KMeans Clustering
- **Elbow method**: Determine the optimal number of clusters by plotting the WCSS (Within-Cluster Sum of Squares).
- **Silhouette score**: Evaluate clustering performance by calculating the silhouette score for different cluster numbers.

#### Agglomerative Clustering
- **Hierarchical clustering**: Visualize clusters using dendrograms to understand how different customers group together.

#### DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
- **Identify clusters**: Use DBSCAN to find clusters based on density, which is suitable for datasets with noise and irregular cluster shapes.

### 4. Data Preprocessing

- **Standardize the data**: Use `StandardScaler` to standardize the dataset, ensuring that features are on a comparable scale.
- **Normalize the data**: Apply `MinMaxScaler` to normalize the data for better clustering performance.

### 5. Visualization

- **t-SNE**: Use t-SNE for dimensionality reduction and visualization of data points in two dimensions before and after clustering.
- **PCA**: Perform Principal Component Analysis (PCA) for reducing dimensionality and visualizing clusters.
- **Radar plots**: Visualize the mean values of each cluster across various features using radar plots to understand the characteristics of each cluster.
