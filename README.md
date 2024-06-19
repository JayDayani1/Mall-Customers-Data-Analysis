# Mall-Customers-Data-Analysis
This repository contains the Jupyter Notebook for analyzing mall customers data. The project focuses on clustering and classification tasks, including k-means clustering and applying various classification algorithms.

## Project Description

### Objective

The objective of this project is to analyze the mall customers dataset to identify customer segments using k-means clustering and then perform classification tasks using various algorithms. The key tasks include:

1. **Clustering**: Performing k-means clustering using Manhattan distance as the distance measure.
2. **Labeling**: Adding a separate column in the dataset to store cluster labels assigned by the k-means algorithm.
3. **Classification**: Applying standard classification algorithms (logistic regression, decision trees, random forest, and Naive Bayes) to the labeled dataset.

## File Description

- **Mall Customers Data Analysis.ipynb**: This is the main Jupyter Notebook file containing all the code, visualizations, and explanations for the project tasks.

## Requirements

To run the notebook, you will need the following Python packages:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`
- `jupyter`

The dataset was analyzed using k-means clustering with Manhattan distance, resulting in distinct customer segments. A new column 'Labels' was added to the dataset to store the cluster labels. Classification tasks were performed using logistic regression, decision trees, random forest, and Naive Bayes algorithms on the labeled dataset, providing insights into the accuracy and performance of each model.
