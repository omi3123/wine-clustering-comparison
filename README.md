# Wine Clustering Comparison

## Project Overview
This project compares multiple unsupervised learning algorithms on the Wine dataset using Python and scikit-learn.

The objective is to analyze how different clustering techniques group data points and to understand the behavior of each algorithm in identifying hidden patterns.

## Algorithms Used
- KMeans Clustering
- DBSCAN (Density-Based Clustering)
- Agglomerative Clustering (Hierarchical)

## Workflow
- Load and preprocess the dataset
- Standardize features
- Apply clustering algorithms
- Determine optimal clusters using Elbow Method and Silhouette Score
- Visualize clusters using PCA
- Compare clustering performance

## Visualizations
- Elbow Method (KMeans)
- Silhouette Score
- PCA-based cluster visualization
- Cluster comparison plots

## Key Insights
- KMeans produced well-defined clusters with clear separation
- Agglomerative clustering showed similar behavior to KMeans
- DBSCAN was sensitive to parameter selection and identified noise points
- PCA helped visualize high-dimensional data effectively

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Learning Outcomes
Through this project, I developed a deeper understanding of:
- Unsupervised learning techniques
- Clustering algorithms and their differences
- Model evaluation using silhouette score
- Dimensionality reduction using PCA

## Repository Contents
- `wine_clustering_comparison.ipynb` — main notebook
- clustering visualizations for analysis and presentation

## Conclusion
This project demonstrates the importance of comparing multiple clustering methods when working with unlabeled data and highlights how different algorithms interpret the same dataset.

## Author
Muhammad Umair Bashir
