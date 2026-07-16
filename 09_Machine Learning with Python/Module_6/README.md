# 🏁 Module 6: Applied Machine Learning & Capstone Classifiers

Welcome to the sixth and final module of the **Machine Learning with Python** course! This repository documents the execution of my capstone projects. It features the construction of an end-to-end data pipeline to predict Titanic passenger survival, followed by a final model evaluating historical weather data to predict rainfall in Australia.

---

## 📝 Core Technical Objectives
* **Practical Synthesis:** Deploying the entire machine learning lifecycle—from raw feature cleaning to model training—over complex real-world datasets.
* **Model Benchmarking:** Building, tuning, and comparing multiple classification models side-by-side to select the absolute best predictive framework.
* **Industrial Validation:** Structuring final evaluations using robust cross-validation grids and pipelines to deliver leak-free, production-grade model results.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

Rather than standard list configurations, my practical capstone deliverables are mapped directly to their specific operational use cases:

| Notebook Pipeline | Integrated ML Estimator / Tool | Production Use Case & Insights |
| :--- | :--- | :--- |
| **[Lab 1: Practice Project (Titanic)](./01_Practice%20Project-v1.ipynb)** | 🚢 **Unified Classification Pipelines** | Handling missing categorical fields, engineering passenger features, and comparing classifiers to optimize survival predictions. |
| **[Lab 2: Capstone Rainfall Classifier](./02_FinalProject_AUSWeather.ipynb)** | 🌧️ **High-Performance Weather Predictor** | Cleaning historical climatic measurements, balancing sparse rain variables, and optimizing classifiers to predict next-day precipitation. |

---

## 💡 Visual Pipeline Reference

Validation and optimization operations mapped systematically by diagnostic requirements:

* **Incomplete Historical Datasets** ➔ Cleaned using **Pandas Imputation** to handle missing variables safely.
* **Raw Categorical Features** ➔ Processed via **One-Hot & Label Encoding** to translate classes into numeric inputs.
* **Comparative Model Matrices** ➔ Evaluated via **Multi-Algorithm Run Sheets** to track scoring stats side-by-side.
* **Final Threshold Tunings** ➔ Optimized via **ROC-AUC & Classification Scores** to maximize detection of rare weather events.

---

## 🎯 Technical Skills Architecture

### 📊 Capstone Classification Pipelines
* 🚢 **Feature Engineering & Imputation:** Handled missing age, deck, and port categories across survival cohorts while avoiding data leakage.
* 🌧️ **Climatic Variable Modeling:** Transformed relative humidity, wind speed vectors, and barometric pressure data to train meteorology estimators.
* 📈 **Performance Scorecards:** Generated detailed classification scorecards to track Accuracy, Precision, Recall, F1-Scores, and ROC-AUC curves.

### 🛠️ Optimization & Production Safeguards
* 📦 **Production Pipeline Enclosures:** Bundled feature scaling, categorical encoding, and classification algorithms into cohesive Scikit-learn pipelines.
* 🔄 **Hyperparameter Search Tuning:** Deployed grid search optimizations to systematically isolate the best model hyperparameters.
* 🛡️ **Generalization Validation:** Leveraged rigorous cross-validation patterns to ensure models remain highly accurate on previously unseen real-world test sets.

---

## 🛠️ Production Tech Stack & Ecosystem

| Core Language | ML Estimator Engine | Data Processing | Vector Mathematics | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) | ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
