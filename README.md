# Iris Species Classification using K-Nearest Neighbors (KNN)

This repository contains a complete implementation of the K-Nearest Neighbors (KNN) algorithm on the classic Iris dataset. The notebook walks through data preprocessing, exploratory data analysis, training a KNN model, and visualizing results to evaluate classification performance.

---

##  Project Overview

The Iris dataset is a multi-class classification problem with three flower species:
- Setosa
- Versicolor
- Virginica

Each instance is described by four numerical features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

##  Key Components

### 1. Data Preprocessing
- Removed the `Id` column as it's non-informative.
- Cleaned the `Species` column (removed prefix like "Iris-").
- Mapped string species labels to numeric targets.

### 2. Exploratory Data Analysis (EDA)
- Used `seaborn` visualizations to understand feature distributions and species separability:
  - Count plot for species distribution.
  - Pair plot to visualize feature relationships across species.

### 3. Feature Scaling
- Standardized the feature values using `StandardScaler` for optimal KNN performance.

### 4. Model Training
- Applied `KNeighborsClassifier` with `k=3`.
- Used `train_test_split` with stratification to maintain class balance.

### 5. Model Evaluation
- Accuracy score
- Classification report (Precision, Recall, F1-Score)
- Confusion matrix (with heatmap)

---

##  Visualizations Included

- Distribution of species
- Pairwise feature relationships
- Confusion matrix heatmap
- Optional PCA and 3D plots (can be added to enhance multidimensional visualization)

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mohan2801/Elevate-Lab_Task6.git
   cd iElevate-Lab_Task6
