# 🤖 Module 4: Predictive Machine Learning & Hyperparameter Tuning

Welcome to the fourth module of the **Applied Data Science Capstone**! In this module, we construct and evaluate supervised machine learning models to solve our core business objective: predicting whether the Falcon 9 first stage will land successfully (`Class = 1` vs. `Class = 0`). 

By framing stage recovery as a binary classification problem, we preprocess launch feature vectors, tune hyperparameters across multiple classification family algorithms using grid search, and evaluate test-set performance to select the best predictive model.

---

## 📝 Core Technical Objectives
* **Dataset Splitting & Preprocessing:** Standardizing numerical feature matrices with `StandardScaler` and establishing train/test splits to prevent data leakage.
* **Hyperparameter Grid Search:** Optimizing decision boundaries across Logistic Regression, Support Vector Machines (SVM), Decision Trees, and K-Nearest Neighbors (KNN) using `GridSearchCV`.
* **Classifier Evaluation & Benchmarking:** Assessing tuned models via accuracy scoring matrices and confusion matrices to isolate the top-performing estimator for launch cost estimation.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core lab deliverables and predictive machine learning models are mapped directly to their targeted operational steps:

| Notebook Pipeline | Integrated Frameworks | Primary Analytical Focus |
| :--- | :--- | :--- |
| **[Lab 1: Predictive Model Optimization](./01_SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb)** | • Scikit-learn<br>• NumPy<br>• Matplotlib | Preprocessing feature sets, configuring cross-validated grid searches across 4 classification algorithms, and evaluating model accuracy on test data. |

---

## 💡 Visual Pipeline Reference

Machine learning operations mapped systematically by diagnostic requirements:

* **Feature Vector Normalization** ➔ Scaled via **StandardScaler** to unify feature scales across payload weights, orbits, and flight sequences.
* **Cross-Validation Partitioning** ➔ Evaluated via **Stratified K-Fold CV** to maintain class proportions across training subsets.
* **Hyperparameter Matrix Tuning** ➔ Optimized via **GridSearchCV** across regularization penalties ($C$), tree depths, kernel choices, and neighbor counts ($k$).
* **Model Selection Audit** ➔ Decision validated via **Confusion Matrix Plots** and test accuracy comparisons across all tuned classifiers.

---

## 🎯 Technical Skills Architecture

### 📊 Supervised Machine Learning
* **Multi-Model Pipeline Training:** Built and trained Logistic Regression, Support Vector Classifiers (SVC), Decision Tree Classifiers, and K-Nearest Neighbors.
* **Hyperparameter Tuning:** Executed automated cross-validated grid searches to tune critical parameters ($C$, $\gamma$, `max_depth`, `criterion`, `n_neighbors`).
* **Confusion Matrix Evaluation:** Analyzed True Positives, False Positives, True Negatives, and False Negatives to evaluate real-world prediction errors.

### 🛠️ Production Data Preprocessing
* **One-Hot Encoding Expansion:** Transformed categorical variables ($Orbit$, $LaunchSite$, $LandingPad$) into numeric indicator vectors.
* **Feature Scaling Integrity:** Applied standard normalization to continuous features after data splitting to ensure zero data leakage.
* **Model Benchmarking:** Ranked algorithms based on hold-out test set accuracy scores to select the best production model.

---

## 🛠️ Production Tech Stack & Ecosystem

| Programming Language | Machine Learning Framework | Data Processing | Vector Math | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) | ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
