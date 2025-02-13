# Customer-Segmentation-for-Marketing
This project implements a machine learning model using clustering techniques to segment customers into distinct groups. The goal is to develop marketing strategies tailored to each customer segment based on their purchasing behavior.

## Overview

This project applies clustering techniques to segment customers into distinct groups based on their demographic and spending characteristics. The goal is to analyze customer behavior and optimize marketing strategies.

## Dataset

The dataset used contains the following columns:

Customer ID: Unique identifier for each customer.

Age: Customer's age in years.

Annual Income (k$): Customer's yearly income in thousands of dollars.

Spending Score (1-100): A score assigned to the customer based on their spending habits, where 1 means minimal spending and 100 indicates high spending.

Product Category: The preferred category of products purchased by the customer.

## Methodology

### Data Preprocessing:

The dataset is loaded using Pandas.

Data is inspected for missing values and overall structure.

Descriptive statistics are computed to understand distributions.

Features are scaled using Min-Max Scaling to ensure uniformity.

### Dimensionality Reduction:

Principal Component Analysis (PCA) is applied to reduce the dataset to two principal components.

Singular Value Decomposition (SVD) is used for additional dimensionality reduction analysis.

### Clustering Techniques:

K-Means Clustering is used to segment the customers into three clusters based on scaled features.

Hierarchical Clustering is applied, and a dendrogram is generated to visualize hierarchical relationships.

### Visualization & Analysis:

A scatter plot is created using PCA results to visualize customer segmentation.

A dendrogram is plotted to illustrate hierarchical clustering.

Cluster statistics are computed to describe the characteristics of each segment.

# Results

The customers were segmented into three distinct groups:

Cluster 1: Young Adults with High Spending

Average age: 33 years

Average income: $68.60k

Spending Score: 70.71/100

This group tends to spend more on experiences and entertainment.

Cluster 2: Older Adults with High Income and Moderate Spending

Average age: 58 years

Average income: $95.47k

Spending Score: 58.86/100

Financially stable but with controlled spending, possibly prioritizing luxury goods or investments.

Cluster 3: Middle-Income Adults with Low Spending

Average age: 42 years

Average income: $49.79k

Spending Score: 21.63/100

More conservative consumers focusing on essential needs.

# Technologies Used

Python

Pandas & NumPy (Data manipulation and preprocessing)

Matplotlib & Seaborn (Data visualization)

Scikit-learn (Machine learning models and clustering algorithms)

SciPy (Hierarchical clustering and dendrogram generation)

# Usage

Clone the repository and ensure you have the necessary dependencies installed.

Load the dataset (customer_data.csv).

Run the script to perform clustering and generate visualizations.
