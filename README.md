# 🌸 KNN in Action — Iris Dataset Classification

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-KNN-yellow?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Language-Python-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Framework-scikit--learn-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Status-Complete-success?style=for-the-badge"/>
</p>

<p align="center">
  <img src="iris.png" width="700" alt="Iris Dataset Visualization"/>
</p>

## 📖 Overview

This project implements a comprehensive K-Nearest Neighbors (KNN) classifier on the famous Iris dataset, featuring advanced hyperparameter tuning, cross-validation strategies, and rich visualizations to understand model behavior and performance.

## ✨ Key Features

### 🔧 Advanced Model Optimization
- **GridSearchCV** — Exhaustive search over specified parameter values
- **RandomizedSearchCV** — Efficient random sampling of hyperparameter space
- **Hyperparameter Tuning** — Optimizing K neighbors and distance metrics

### 📊 Comprehensive Evaluation
- **Nested Cross-Validation** — Unbiased performance estimation
- **Accuracy vs. K Analysis** — Understanding bias-variance tradeoff
- **Metric Comparison** — Euclidean, Manhattan, and Minkowski distances
- **Confusion Matrix** — Detailed classification breakdown

### 🎨 Rich Visualizations

#### 🌀 Decision Boundaries (PCA 2D Projection)
Visualizes how KNN partitions the feature space, demonstrating class separability and decision boundary smoothness across different K values.

#### 🎛️ Feature Importance (Permutation-based)
Reveals which features contribute most to classification accuracy. Petal dimensions (length and width) emerge as dominant predictors, aligning with botanical expectations.

#### 📈 Accuracy vs. K Curve
Illustrates the classic bias-variance tradeoff as K increases, helping identify the optimal number of neighbors.

#### 🔥 Performance Heatmap (K × Distance Metric)
A comprehensive comparison matrix showing accuracy across:
- **Euclidean Distance** — Standard L2 norm
- **Manhattan Distance** — L1 norm for grid-based distance
- **Minkowski Distance** — Generalized metric

## 🛠️ Technologies Used

- **Python 3.x**
- **scikit-learn** — ML algorithms and tools
- **NumPy** — Numerical computing
- **Pandas** — Data manipulation
- **Matplotlib/Seaborn** — Visualization
- **Colab Notebook** — Interactive development

---

## 📈 Results Summary

Both GridSearchCV and RandomizedSearchCV consistently achieve ~96–97% accuracy on the Iris dataset, with optimal performance occurring at K=7–10 using distance-weighted KNN and Euclidean/Minkowski metrics, while feature importance confirms that petal length and petal width are the dominant drivers of species classification.


## 🙏 Acknowledgments

- UCI Machine Learning Repository for the Iris dataset
- scikit-learn community for excellent documentation
- R.A. Fisher for the original Iris dataset (1936)

---

<p align="center">
  Made with ❤️ for Machine Learning Education
</p>
