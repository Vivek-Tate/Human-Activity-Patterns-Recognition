# Human Activity Patterns Recognisition: Clustering and Dimensionality Reduction

## Project Overview

This project focuses on the clustering and visualisation of human activity patterns using smartphone sensor data. The dataset used for this project is the Human Activity Recognition (HAR) dataset, which includes 561 features representing various aspects of sensor dynamics during different activities.

## Dataset

The dataset used in this project is the UCI Human Activity Recognition dataset, which can be found [here](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones). This dataset includes measurements collected from smartphone sensors while participants performed various activities.

## Project Workflow

1. **Detailed Analysis of Given Data**:
   - **Outliers & Noise Detection**: Identify and analyse outliers and noise present in the dataset.
   - **Correlation Matrix**: Generate and examine the correlation matrix to understand relationships between different features.
   - **Structural Analysis through Graph**: Conduct a structural analysis of the data using graph-based methods to gain insights into the underlying patterns.

2. **Clustering with DBSCAN**:
   - Find the best hyper-parameters for the DBSCAN algorithm.
   - Implement the DBSCAN clustering algorithm.
   - Analyse the quality of the clustering results.

3. **Dimensionality Reduction**:
   - Train a dimensionality reduction method using Linear Discriminant Analysis (LDA).
   - Visualise the clusters in the reduced feature space for better interpretability.

## Results

The final output includes a visual representation of the clusters in a reduced feature space, providing insights into the different activity patterns recognised by the smartphone sensors.

## Acknowledgements

The dataset used in this project is provided by the UCI Machine Learning Repository. Special thanks to the creators of the dataset for their contributions. You can find more information about the dataset [here](https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones).
