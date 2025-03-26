# K-Means Clustering Implementation

## Overview
This project implements the K-Means clustering algorithm from scratch using Python. The script loads a dataset, normalizes the data, applies the K-Means algorithm for k=2 and k=3, and visualizes the clustering results.

## Requirements
Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib
```

## Files
- `kmeans.py`: Main script containing the K-Means implementation and visualization.
- `kmeans_blobs.csv`: The dataset used for clustering (Ensure this file is in the same directory as the script).

## Implementation Details
1. **Data Preprocessing:**
   - Reads the dataset from a CSV file.
   - Normalizes the dataset using Min-Max Scaling.

2. **K-Means Clustering Function:**
   - Initializes k random centroids.
   - Assigns each data point to the nearest centroid.
   - Updates centroids based on the mean of assigned points.
   - Iterates until convergence or reaching max iterations.

3. **Visualization:**
   - Generates scatter plots for k=2 and k=3.
   - Colors each point based on its cluster.
   - Highlights centroids in red and labels them.

## Usage
Run the script in Jupyter Notebook or as a standalone Python file:

```python
python kmeans.py
```


