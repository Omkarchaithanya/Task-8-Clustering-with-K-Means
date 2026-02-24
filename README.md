# K-Means Clustering with Scikit-learn

## Overview

This project demonstrates **unsupervised learning** using the K-Means clustering algorithm.  
It includes:

- Data preprocessing (feature scaling)
- Elbow Method to determine optimal number of clusters
- K-Means model fitting
- Cluster visualization using PCA
- Evaluation using Silhouette Score

The implementation uses the Iris dataset from scikit-learn.

---

## Objective

Perform clustering using K-Means and evaluate cluster quality.

---

## Tools & Libraries

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

The project uses the built-in **Iris dataset**, which contains:

- 150 samples
- 4 numerical features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width

Since K-Means is unsupervised, target labels are not used during training.

---

## Project Workflow

### 1. Data Loading
Load dataset using `sklearn.datasets.load_iris()`.

### 2. Feature Scaling
Standardize features using `StandardScaler` to ensure equal contribution to distance calculations.

### 3. Elbow Method
Compute inertia for K = 1 to 10 and plot the curve to identify the optimal number of clusters.

### 4. Model Training
Fit K-Means with optimal K (K=3 for Iris).

### 5. Evaluation
Compute Silhouette Score to measure clustering quality.

### 6. Visualization
Use PCA to reduce dimensions to 2D and visualize clusters.

---

## How to Run

### 1. Install Dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
