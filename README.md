# Task 3 - Clustering Algorithms in Machine Learning

This repository contains the solution for **Task 3** of the SkillCraft Machine Learning series. The focus of this task is to apply various clustering algorithms to explore patterns and segment the data into meaningful clusters.

## Contents

- **Task 3.ipynb**: A Jupyter Notebook that demonstrates the application of clustering algorithms such as:
  - K-Means Clustering
  - Hierarchical Clustering
  - DBSCAN (Density-Based Spatial Clustering)
  
- **Data**: The dataset used for clustering analysis. The data is preprocessed to ensure compatibility with the clustering algorithms.

## Overview

In this task, the following steps are covered:
1. **Data Loading**: Importing and inspecting the dataset.
2. **Data Preprocessing**: Handling missing values, scaling features, and preparing the data for clustering.
3. **Clustering Methods**:
   - **K-Means**: Applied for partitioning data into K clusters based on distance.
   - **Hierarchical Clustering**: Used to create a dendrogram and identify clusters based on similarity.
   - **DBSCAN**: Applied to group data points based on density, handling noise points effectively.
4. **Evaluation**: Visualizing clusters and evaluating the performance of different algorithms using metrics like inertia, silhouette score, and dendrogram analysis.

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/pavani-1510/SCT_ML_3.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```
   jupyter notebook Task%20-%203.ipynb
   ```

## Results

The clustering methods provided insights into the structure of the data. Each algorithm has its strengths, depending on the nature of the dataset.

## Dependencies

- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Matplotlib
- Seaborn
- NumPy
- Pandas
