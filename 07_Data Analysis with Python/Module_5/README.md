# 🎯 Module 5: Model Evaluation, Regularization, & Hyperparameter Tuning

Welcome to the fifth module of my Data Analysis track! This repository focuses on model optimization and validation strategies—diagnosing generalization errors, balancing the bias-variance trade-off, applying regularization techniques, and conducting cross-validated grid searches to isolate the best-performing model setup.

## 📝 Module Overview
In this module, I focused on moving beyond simple model training to master model validation, refinement, and optimization. I learned how to critically interpret discrepancies between training and testing error scores to evaluate a model's true generalization performance and identify early warning signs of underfitting or overfitting.

Through rigorous hands-on labs, I studied the **bias-variance trade-off** and learned how to mitigate overfitting by implementing **Ridge Regression ($L_2$ regularization)**. By introducing a regularization penalty ($\alpha$), I successfully constrained model coefficients and compared the stabilized results against standard ordinary least squares (OLS) linear regressions. Furthermore, I automated the hyperparameter optimization process using **Grid Search (`GridSearchCV`)**, systematically scanning parameter combinations to discover the highest-performing architecture based on robust cross-validation data splits. I deployed these refinement workflows to optimize price-prediction models for both the *Used Cars* and *Laptops* datasets.

---

## 🧪 Hands-On Labs
This module features two optimization and refinement notebooks. Click on any lab to explore the code:

* 📂 **[`01_Model_Evaluation_and_Refinement_cars.ipynb`](01_Model_Evaluation_and_Refinement_cars.ipynb)**
    * *Applied model optimization on the Used Car Pricing dataset, tracking training/testing metrics and evaluating polynomial degree stability.*
* 📂 **[`02_practice_model_evaluation.jupyterlite.ipynb`](02_practice_model_evaluation.jupyterlite.ipynb)**
    * *An applied model refinement lab utilizing Ridge regularization and cross-validated grid search to optimize laptop pricing predictions.*

---

## 🎯 Learning Objectives Completed

* ⚖️ **Generalization Performance Auditing:** Analyzed the divergence between training and validation error distributions to identify overfitting or underfitting.
* 🧠 **Bias-Variance Trade-Off Optimization:** Differentiated structural data modeling errors, applying targeted parameter and complexity adjustments to find an optimal balance.
* 🛡️ **L2 Regularization (Ridge Regression):** Implemented `sklearn.linear_model.Ridge` equations to penalize extreme coefficients, reducing model sensitivity to multicollinearity and noisy features.
* 🎛️ **Automated Hyperparameter Tuning:** Orchestrated cross-validated **Grid Search** procedures to systematically audit model configurations and pinpoint the best hyperparameter settings.
* 📊 **Cross-Validation Integration:** Utilized multi-fold cross-validation frameworks to verify that performance scoring metrics remained stable and free of data selection bias.
* 🏆 **Predictive Pipeline Refinement:** Upgraded standalone regression baselines into optimized, production-ready price estimation models with minimized test-set error variances.

---

## 🛠️ Tech Stack & Tools Used
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
