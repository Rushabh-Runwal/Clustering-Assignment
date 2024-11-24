# Data Mining Assignment: Clustering Techniques

This repository contains the implementation of various clustering algorithms as part of a data mining course assignment. Each clustering method has been implemented in a Colab notebook with clear documentation, explanations, and examples.

---
## Youtube Video
- [YouTube Tutorial](#youtube-tutorials)
- [YouTube Tutorial](#youtube-tutorials)

## Table of Contents
1. [K-Means Clustering]: [https://colab.research.google.com/drive/13lnCxYp5qhCHQZQ-NRFzmhza6v_GG6Ae?usp=sharing]
2. [Hierarchical Clustering]: (https://colab.research.google.com/drive/1KdO7BnjS61OL4jWeQPK3yq5iTAbKXbfR?usp=sharing)
3. [Gaussian Mixture Models Clustering]: (https://colab.research.google.com/drive/1jDgsroIpxJvbNi2gowjY13DRBrJZ_7zT?usp=sharing)
4. [DBSCAN Clustering using PyCaret]: (https://colab.research.google.com/drive/1bS2K_6V-5PlaG7hu633Z7YqAEDaurCqD?usp=sharing)
5. [Anomaly Detection using PyOD]: (https://colab.research.google.com/drive/1IA2xFGH9RVZX32hNJXXI_MbgCEpmQu7I?usp=sharing)
6. [Time Series Clustering using Pre-Trained Models]: (https://colab.research.google.com/drive/1rHB66M9abDPlVmhNNGhJIOKlcIU8QdXz?usp=sharing)
7. [Document Clustering with LLM Embeddings]: (https://colab.research.google.com/drive/1XfHLKsyzfRqHx-TBgQngoJcpwlovoC2Y?usp=sharing)
8. [Image Clustering using ImageBind LLM Embeddings]: (https://colab.research.google.com/drive/1IcMH50Lgsb7GPk5DtYB_K3mlDt5t0IL-?usp=sharing)
9. [Audio Clustering using ImageBind LLM Embeddings]: (https://colab.research.google.com/drive/1di_Cp5WZkJqlJBxGgvQtH6bOx3NMlxnO?usp=sharing)

---

## Clustering Techniques

### 1. K-Means Clustering
- **Description**: Implemented K-Means clustering from scratch, using a synthetic dataset. The algorithm iteratively assigns points to the nearest centroid and updates the cluster centroids.
- **Highlights**:
  - Synthetic dataset with visualizations.
  - Evaluation metrics: SSD and Silhouette Score.

---

### 2. Hierarchical Clustering
- **Description**: Explored hierarchical clustering (agglomerative) using an existing implementation. Demonstrated dendrogram plotting and linkage methods.
- **Highlights**:
  - Use of linkage types (e.g., single, complete).
  - Visualization of dendrograms for clustering insights.

---

### 3. Gaussian Mixture Models Clustering
- **Description**: Used Gaussian Mixture Models (GMM) for clustering a dataset. GMM assumes data points are drawn from multiple Gaussian distributions.
- **Highlights**:
  - Compared GMM with K-Means.
  - Visualized probability distributions.

---

### 4. DBSCAN Clustering using PyCaret
- **Description**: Leveraged PyCaret’s clustering module to implement DBSCAN, a density-based clustering algorithm. Showcased its ability to handle noise and non-spherical clusters.
- **Highlights**:
  - Automatic parameter tuning.
  - Cluster quality evaluation.

---

### 5. Anomaly Detection using PyOD
- **Description**: Demonstrated anomaly detection using PyOD (Python Outlier Detection). Worked with both univariate and multivariate data.
- **Highlights**:
  - Applied Isolation Forest and One-Class SVM.
  - Evaluated using precision-recall metrics.

---

### 6. Time Series Clustering using Pre-Trained Models
- **Description**: Implemented clustering of time-series data using pre-trained models and embeddings. Worked with state-of-the-art libraries.
- **Highlights**:
  - Embedded time series into feature space.
  - Clustering visualization for time-series patterns.

---

### 7. Document Clustering with LLM Embeddings
- **Description**: Clustered textual data using embeddings generated by state-of-the-art LLMs (e.g., Sentence Transformers). Visualized the document clusters using dimensionality reduction.
- **Highlights**:
  - Used cosine similarity for clustering.
  - Real-world document dataset example.

---

### 8. Image Clustering using ImageBind LLM Embeddings
- **Description**: Performed clustering on images by leveraging embeddings from ImageBind, a powerful pre-trained model for multimodal embeddings.
- **Highlights**:
  - Visualized cluster centroids as representative images.
  - Image similarity-based clustering.

---

### 9. Audio Clustering using ImageBind LLM Embeddings
- **Description**: Clustered audio features using embeddings extracted from ImageBind. Demonstrated the grouping of similar audio samples.
- **Highlights**:
  - Audio feature extraction using pretrained models.
  - Applied clustering algorithms like K-Means and DBSCAN.

---

## How to Use This Repository
1. Open each Colab notebook using the provided links.
2. Follow the instructions in the notebook to run the code and visualize the results.
3. Ensure necessary libraries (e.g., NumPy, scikit-learn, PyCaret, PyOD) are installed in the Colab environment.

---

