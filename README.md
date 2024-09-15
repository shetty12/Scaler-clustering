
# Scaler Clustering Analysis Project

This project focuses on performing clustering analysis using hierarchical and agglomerative clustering methods. The goal is to group the data points into distinct clusters based on their similarities. Clustering techniques like these are widely used for segmentation tasks in various industries, such as customer segmentation, market research, and anomaly detection.

**Project Overview**

Clustering is an unsupervised machine learning technique that groups data points based on their features. This project demonstrates how to use Hierarchical Clustering and Agglomerative Clustering to cluster a dataset into meaningful groups. By visualizing the clusters, we can identify patterns in the data that may not be immediately obvious.

**Key Steps Involved**:
Data Preprocessing: Cleaning and transforming the dataset to make it suitable for clustering.

**Hierarchical Clustering**: Building a dendrogram to visualize how clusters are formed based on the data's distance matrix.

**Agglomerative Clustering**: Using a predefined number of clusters to group the data.

**Visualization**: Visualizing the dendrogram and clusters to interpret the results.

**Objectives**
**Group Data Points**: Use hierarchical and agglomerative clustering techniques to group data points based on their similarity.

**Visualize Clusters**: Use dendrograms and other visualization techniques to understand how the clusters are formed.

**Understand Data Structure**: Identify patterns and relationships in the dataset that can be used for further analysis

**Data Preprocessing**
Data preprocessing is crucial to ensure that the clustering algorithms perform well. In this project, key preprocessing steps include:

**Handling Missing Values**: Ensuring there are no missing values that could impact clustering.
Scaling the Data: Scaling the features to ensure that distance-based algorithms like clustering are not biased by features with larger ranges.


__Clustering Techniques__

1) **Hierarchical Clustering**

Method: Hierarchical clustering is a bottom-up approach where each data point starts as its own cluster. The algorithm successively merges pairs of clusters until all points are part of a single cluster.

Tool: The scipy.cluster.hierarchy module is used to compute the distance matrix and generate a dendrogram for visualization.
Dendrogram: A dendrogram is used to visualize how clusters are merged. The height of each merge represents the distance between clusters.

2) **Agglomerative Clustering**
Method: This is a form of hierarchical clustering where the number of clusters is predefined. The algorithm groups data points based on their similarity until the specified number of clusters is achieved.
Tool: The AgglomerativeClustering class from sklearn is used to cluster the data into a predefined number of clusters.

**Visualization**
The clustering results are visualized using the dendrogram for hierarchical clustering and scatter plots for agglomerative clustering.

**Dendrogram**:
The dendrogram provides a visual representation of the hierarchical clustering process and allows us to determine the optimal number of clusters.

**Scatter Plot for Clusters**:
A scatter plot is used to visualize the data points along with their cluster assignments


**Results**

**Hierarchical Clustering**: The dendrogram helps visualize the relationships between data points, providing insight into how many clusters to select.

**Agglomerative Clustering**: The dataset was successfully clustered into three distinct groups, with each data point assigned to a cluster based on its similarity to others.


## Badges



[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
![Python](https://img.shields.io/badge/python-3.8-blue.svg)
![Pandas](https://img.shields.io/badge/pandas-1.2.4-blue.svg)
![NumPy](https://img.shields.io/badge/numpy-1.19.2-orange.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.3.4-orange.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-yellow.svg)
![Scipy](https://img.shields.io/badge/scipy-1.6.0-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)


## Deployment

Clone the repository:

```bash
  git clone <repository-url>
```
Install required Python libraries:

```bash
  pip install pandas numpy matplotlib scikit-learn
```
Open the notebook:
```bash
    jupyter notebook Scaler_Clustering.ipynb
