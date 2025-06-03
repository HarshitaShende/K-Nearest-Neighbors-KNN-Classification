# Task-6-K-Nearest-Neighbors-KNN-Classification
K-Nearest Neighbors (KNN) Classification


## 🎯 Objective

Implement the **K-Nearest Neighbors (KNN)** algorithm to perform classification using a well-known dataset and visualize how K impacts model performance and decision boundaries.

---

## 🧰 Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📊 Dataset

- **Name:** Iris Dataset
- **Source:** Scikit-learn (`sklearn.datasets.load_iris`)
- **Description:** 150 samples with 4 numeric features to classify iris species (Setosa, Versicolor, Virginica).

---

## ✅ Workflow Summary

### 1. Load and Preprocess Dataset
- Loaded Iris dataset into a DataFrame.
- Normalized features using `StandardScaler` to improve distance-based calculations.

### 2. Train-Test Split
- Used `train_test_split` to divide data into training (80%) and testing (20%).

### 3. Train KNN Classifier
- Used `KNeighborsClassifier` from Scikit-learn.
- Trained models for different values of K: 1, 3, 5, 7, 9.

### 4. Evaluate Model
- Calculated **Accuracy**, **Confusion Matrix**, and **Classification Report** for each K.
- Plotted Accuracy vs K to find optimal K.

### 5. Visualize Decision Boundary
- Used only the first 2 features for 2D visualization.
- Plotted decision regions for K=5 to understand class separation.




