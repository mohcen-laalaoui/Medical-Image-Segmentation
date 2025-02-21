# 🏥 Medical Image Segmentation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)


This project applies **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** to segment medical images and detect structures such as blood cells. The algorithm clusters image features and identifies noise, aiding in medical image analysis.

## 🚀 Features
- 🖼 **Processes multiple medical images** (up to 50 for visualization).
- 🏷 **Uses DBSCAN for unsupervised clustering**.
- 📊 **Evaluates clustering with metrics** (Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index).
- 📉 **Plots segmented results for visual analysis**.

## 📦 Installation
  Clone the repository and install dependencies:
    ```bash
    
      git clone https://github.com/mohcen-laalaoui/Medical-Image-Segmentation.git
      cd Medical-Image-Segmentation

## 📊 Clustering Metrics
After running DBSCAN, the project calculates:

- Silhouette Score → Measures cluster quality
- Davies-Bouldin Index → Evaluates cluster separation
- Calinski-Harabasz Index → Measures intra-cluster variance

## 🛠 Technologies Used
Python 🐍
OpenCV
NumPy
Matplotlib
Scikit-Learn (DBSCAN, Clustering Metrics)

## 📌 To-Do
 - Improve feature extraction
 - Experiment with different DBSCAN parameters
 - Compare with K-Means segmentation


# 👨‍💻 Author
## 📌 Mohcen Laalaoui
  💼 Machine Learning & Data Science Enthusiast
