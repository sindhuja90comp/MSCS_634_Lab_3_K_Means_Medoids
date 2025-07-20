# MSCS 634 Lab 3: K-Means & K-Medoids Clustering

This repository contains the implementation and analysis of K-Means and K-Medoids clustering algorithms as part of Lab 3 for MSCS 634. The project demonstrates clustering techniques using Python in Jupyter Notebooks, applying them to sample datasets and visualizing the results.


## Purpose of Lab Work

The purpose of this lab is to implement and compare K-Means and K-Medoids clustering algorithms. The objective is to understand how these algorithms group data, evaluate their effectiveness on different datasets, and observe their behavior in terms of performance and cluster quality.


## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [References](#references)
- [Author](#author)

## Overview

Clustering is an unsupervised machine learning technique used to group similar data points together. In this lab, both K-Means and K-Medoids algorithms are implemented to compare their performance and output on different datasets. Visualizations are provided to illustrate how the clusters are formed.

## Project Structure

```
MSCS_634_Lab_3_K_Means_Medoids/
├── KMeans_Clustering.ipynb
├── KMedoids_Clustering.ipynb
├── README.md
```
- `KMeans_Clustering.ipynb`: Implementation and analysis of K-Means algorithm.
- `KMedoids_Clustering.ipynb`: Implementation and analysis of K-Medoids algorithm.
- `data/`: Folder containing datasets used for clustering.
- `README.md`: Project documentation.

## Requirements

- Python 3.x
- Jupyter Notebook
- numpy
- pandas
- matplotlib
- scikit-learn
- scikit-learn-extra (for K-Medoids)
- seaborn (optional, for enhanced visualization)

Install required packages via pip:
```bash
pip install numpy pandas matplotlib scikit-learn scikit-learn-extra seaborn
```

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/sindhuja90comp/MSCS_634_Lab_3_K_Means_Medoids.git
    cd MSCS_634_Lab_3_K_Means_Medoids
    ```

2. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

3. Open either `KMeans_Clustering.ipynb` or `KMedoids_Clustering.ipynb` and run the cells step by step.

## Results

- Comparative analysis of K-Means and K-Medoids clustering.
- Visualization of clusters and centroids/medoids.
- Discussion on the strengths and weaknesses of each algorithm.

*Sample visualizations and findings can be found within the notebooks.*

## References

- [Scikit-Learn User Guide: Clustering](https://scikit-learn.org/stable/modules/clustering.html)
- [scikit-learn-extra documentation](https://scikit-learn-extra.readthedocs.io/en/latest/)


## Author

- [Sindhuja90comp](https://github.com/sindhuja90comp)


## Key Insights and Observations

- K-Means is efficient and works well with large datasets but is sensitive to outliers.
- K-Medoids is more robust to outliers and noise, but can be computationally intensive for large datasets.
- Visualizations in the notebooks help demonstrate the difference in cluster assignments and centroid/medoid placement.
- The choice of number of clusters (k) and initialization method can significantly impact results for both algorithms.

## Challenges Faced and Decisions Made

- Handling outliers was challenging; K-Means sometimes produced poor clusters due to extreme values.
- Deciding on the optimal number of clusters required experimenting with different metrics (e.g., silhouette score, elbow method).
- Using the correct library for K-Medoids (scikit-learn-extra) and ensuring compatibility with the dataset required additional setup.
- Balancing between computation time and clustering accuracy influenced the choice between algorithms.


