# Incremental DBSCAN

## Overview

This project was developed as the final project for the **Machine Learning** course at the **University of Economics Ho Chi Minh City (UEH)**.

The objective of this project is to implement the **Incremental DBSCAN** clustering algorithm, which incrementally updates existing clusters when new data arrives instead of performing clustering from scratch. This approach helps reduce computational costs while maintaining clustering quality, making it suitable for dynamic or continuously growing datasets.

The project also evaluates the effectiveness of the proposed algorithm by comparing it with the traditional **DBSCAN** and **K-Means** algorithms using standard clustering evaluation metrics and visualization techniques.

---

## Objectives

- Understand the principles of density-based clustering.
- Implement the Incremental DBSCAN algorithm in Python.
- Compare Incremental DBSCAN with traditional DBSCAN and K-Means.
- Evaluate clustering performance using multiple metrics.
- Visualize clustering results for better interpretation.

---

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- OpenPyXL

---

## Project Structure

```text
incremental-dbscan/
│
├── dataset/
├── images/
├── notebook/
├── report/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Dataset

The project uses a synthetic **Moon** dataset generated for clustering experiments. The dataset consists of two-dimensional points that are suitable for evaluating density-based clustering algorithms.

---

## Implemented Algorithms

- Incremental DBSCAN
- DBSCAN
- K-Means

---

## Evaluation Metrics

The clustering performance is evaluated using the following metrics:

- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index

These metrics provide a comprehensive assessment of clustering quality in terms of cluster cohesion and separation.

---

## Project Highlights

- Incremental clustering implementation.
- Comparison with traditional clustering algorithms.
- Performance evaluation using multiple metrics.
- Data visualization for clustering analysis.
- Modular implementation using Python and Jupyter Notebook.

---

## Author

**Tran Quoc Tuan**

Computer Science Student

University of Economics Ho Chi Minh City (UEH)
