# 🌀 Module 4: Unsupervised Learning — Advanced Clustering & Dimensionality Reduction

Welcome to the fourth module of the **Machine Learning with Python** course! This repository documents my implementation of unsupervised learning workflows. It covers partitioning and density-based clustering models (K-Means, DBSCAN, HDBSCAN) and high-dimensional space compression techniques (PCA, t-SNE, UMAP) designed to extract structural features from unlabeled datasets.

---

## 📝 Core Technical Objectives
* **Latent Pattern Extraction:** Discovering hidden structural relationships within complex, raw feature profiles without predefined target categories.
* **Density & Centroid Clustering:** Grouping high-dimensional observations based on vector proximity metrics or contiguous high-density spaces.
* **Dimensionality Compression:** Projecting massive dimensional arrays into simplified coordinate zones while maintaining maximum variance or structural manifolds.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

Rather than standard list configurations, my practical lab deliverables and materials are mapped directly to their specific operational use cases:

| Notebook Pipeline | Integrated ML Estimator | Production Use Case & Insights |
| :--- | :--- | :--- |
| **[Lab 1: Customer Segmentation](./01_K-Means-Customer-Seg-v1.ipynb)** | 🎯 **K-Means Clustering** | Partitioning behavioral consumer metrics into distinct demographic profiles using centroid distance optimization. |
| **[Lab 2: Spatial Density Comparison](./02_Comparing-DBScan-HDBScan-v1.ipynb)** | 🗺️ **DBSCAN / HDBSCAN** | Comparing static density scanning against hierarchical density-based clustering to isolate arbitrarily shaped geographical clusters and noise outliers. |
| **[Lab 3: Feature Space Compression](./03_PCA-v1.ipynb)** | 📉 **Principal Component Analysis (PCA)** | Orthogonally projecting redundant features onto linear directions of maximum variance to simplify downstream modeling. |
| **[Lab 4: High-Dimensional Visualizations](./04_tSNE-UMAP-v1.ipynb)** | 🎨 **t-SNE & UMAP** | Constructing non-linear projections to map complex manifold structures into human-readable 2D/3D representations. |

---

## 💡 Visual Pipeline Reference

Estimator configurations mapped systematically by incoming data structure requirements:

* **Spherical, Balanced Clusters** ➔ Deployed via **K-Means Clustering** to partition observations using centroid metrics.
* **Arbitrary, Noise-Heavy Arrays** ➔ Deployed via **DBSCAN** to isolate density-connected groups and discard outliers.
* **Multi-Scale Density Variations** ➔ Deployed via **HDBSCAN** to automatically identify hierarchical cluster steps.
* **Linear Redundancy Simplification** ➔ Deployed via **PCA** to aggregate correlated metrics into orthogonal components.
* **Manifold Visualizations** ➔ Deployed via **t-SNE / UMAP** to preserve local or global structures in low dimensions.

---

## 🎯 Technical Skills Architecture

### 🌀 Advanced Clustering Architectures
* 🎯 **Centroid Optimization:** Implemented Euclidean distance metrics to iteratively map stable clustering assignments and evaluated boundaries via Silhouette analysis.
* 🗺️ **Density Neighborhood Mapping:** Managed core, border, and noise designations using search radii ($\epsilon$) and minimum point criteria.
* 🌿 **Hierarchical Mutual Reachability:** Applied minimal spanning tree extractions to define clusters across varying levels of density.

### 📉 Dimensionality Reduction & Projection
* 📉 **Eigenvalue Decomposition:** Programmed covariance matrix projections to maximize captured variance across principal orthogonal axes.
* 🎨 **Probability-Based Local Embedding:** Constructed probability distributions over vector pairs to map local neighborhood layouts using t-SNE.
* 📐 **Fuzzy Simplicial Set Projection:** Modeled geometric manifold projections using UMAP to maintain global data structures during dimension reduction.

---

## 🛠️ Production Tech Stack & Ecosystem

| Core Language | ML Estimator Engine | Unsupervised Extensions | Vector Mathematics | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) | ![UMAP](https://img.shields.io/badge/UMAP-black?style=flat&logo=python&logoColor=white) | ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
