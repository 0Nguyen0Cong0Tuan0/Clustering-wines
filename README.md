# Wines Clustering

This project explores clustering techniques applied to the Wine dataset. It demonstrates the use of various clustering algorithms, visualizations, and analyses to derive meaningful insights from the data.

## Overview
The goal of this project is to understand and implement clustering algorithms, visualize the results, and analyze the outcomes. The Wine dataset is used as the basis for clustering experiments.

## Algorithms Implemented
1. **K-Means Clustering**
2. **Agglomerative Clustering**
   - Linkage methods: `ward`, `average`, `complete`, `single`
3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

## Visualizations
The project includes the following visualizations:
- Scatter plots of clusters in 2D using PCA for dimensionality reduction.
- Dendrograms to visualize hierarchical clustering structures.

## How to Run
1. Clone the repository:
   ```sh
   git clone <repository-url>
    ```
2. Install the required dependencies (see below).
3. Open `main.ipynb` in Jupyter Notebook or any compatible IDE.
4. Run the notebook cells sequentially to reproduce the results.

## Dependencies

The project uses the following Python libraries:

- `numpy`
- `matplotlib`
- `scikit-learn`
- `scipy`

Install the dependencies using:
```sh
pip install numpy matplotlib scikit-learn scipy
```

## Insights
- **Agglomerative Clustering**: The dendrogram using `ward` linkage reveals a clear hierarchical structure with three dominant clusters.
- **DBSCAN**: Effective in detecting noise and clusters with varying densities by tuning `eps` and `min_samples`.
- **K-Means**: Provides compact clusters but is sensitive to initialization and outliers.