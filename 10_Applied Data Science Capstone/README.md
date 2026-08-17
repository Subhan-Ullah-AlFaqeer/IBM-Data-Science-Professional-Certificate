
# 🚀 IBM Data Science Professional Certificate: Applied Data Science Capstone

Welcome to the central repository for the **Applied Data Science Capstone**—the final capstone project of the **IBM Data Science Professional Certificate** and **Applied Data Science with Python Specialization**.

In this capstone, you assume the role of a Lead Data Scientist at an aerospace startup competing directly with **SpaceX**. SpaceX advertises Falcon 9 launches for **$62 million**, compared to upwards of **$165 million** for other providers. Much of these savings stem from SpaceX's ability to recover and reuse the first-stage rocket booster. By predicting whether the Falcon 9 first stage will land successfully, our startup can estimate launch costs accurately and place competitive bids for launch contracts.


## 🗺️ Master Curriculum & Core Learning Architecture

🚀 APPLIED DATA SCIENCE CAPSTONE<br>
├── 🛰️ Module 1: Data Collection (API & Web Scraping) & Data Wrangling<br>
├── 🔍 Module 2: Exploratory Data Analysis (EDA) with SQL & Data Visualization<br>
├── 🗺️ Module 3: Interactive Visual Analytics (Folium Maps & Plotly Dash)<br>
├── 🤖 Module 4: Predictive Machine Learning & Hyperparameter Optimization<br>
└── 📢 Module 5: Executive Capstone Presentation & Strategic Findings<br>



## 🧪 Specialization Laboratory & Core Artifact Matrix

This master index maps every notebook, script, database, and deliverable across all 5 modules directly to its targeted operational environment:

| Academic Phase | Core Lab Deliverables | Primary Analytical Focus |
| :--- | :--- | :--- |
| **Module 1** | • [Lab 1: SpaceX REST API Ingestion](./Module_1/01_jupyter-labs-spacex-data-collection-api-v2.ipynb)<br>• [Lab 2: Wikipedia Web Scraping](./Module_1/02_jupyter-labs-webscraping.ipynb)<br>• [Lab 3: Feature Wrangling](./Module_1/03_labs-jupyter-spacex-Data%20wrangling-v2.ipynb) | Extracting telemetry logs from the SpaceX API, scraping launch records with `BeautifulSoup`, cleaning missing values, and engineering the binary target variable (`Class`). |
| **Module 2** | • [Lab 1: SQL Data Analysis](./Module_2/01_jupyter-labs-eda-sql-coursera_sqllite.ipynb)<br>• [Lab 2: Visual EDA](./Module_2/02_jupyter-labs-eda-dataviz-v2.ipynb)<br>• [Database: SQLite Instance](./Module_2/my_data1.db) | Querying launch databases with SQLite, analyzing payload distributions across orbits, and visualizing success trends over time using Seaborn and Matplotlib. |
| **Module 3** | • [Lab 1: Spatial Proximity Maps](./Module_3/01_lab-jupyter-launch-site-location-v2.ipynb)<br>• [App Script: Plotly Dash Web App](./Module_3/spacx_dash.py)<br>• [Dataset: Geospatial Launch Records](./Module_3/spacex_launch_geo.csv) | Constructing interactive maps with `Folium` to measure launch site proximity to coastlines/railways, and building reactive dashboard web apps using `Plotly Dash`. |
| **Module 4** | • [Lab 1: Machine Learning Models](./Module_4/01_SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb) | Preprocessing feature matrices, standardizing inputs, and executing cross-validated `GridSearchCV` hyperparameter tuning across Logistic Regression, SVM, Decision Trees, and KNN. |
| **Module 5** | • [Deliverable: Executive Deck](./Module_5/Executive_Presentation.pdf)<br>• [Deliverable: Capstone Report](./Module_5/Capstone_Final_Report.md) | Synthesizing the entire data pipeline, exploratory findings, geospatial maps, and model benchmark matrices into an executive-ready presentation and report. |

---

## 💡 Visual Pipeline Reference

The end-to-end data science methodology applied across this capstone project:

* **Data Collection & Cleaning** ➔ Extracted via **SpaceX REST API & BeautifulSoup** -> Transformed via **Pandas Normalization**.
* **Exploratory Relational Queries** ➔ Analyzed via **SQLite3 Databases** to aggregate payload masses and flight trends.
* **Geospatial & Interactive Web Analytics** ➔ Rendered via **Folium MarkerClusters & Plotly Dash Callbacks**.
* **Predictive Boundary Optimization** ➔ Evaluated via **Logistic Regression, SVM, Decision Trees, & KNN** tuned with `GridSearchCV`.
* **Stakeholder Reporting** ➔ Communicated via **Executive Storyboards & Confusion Matrix Benchmarks**.

---

## 🎯 Global Technical Competencies Mastered

### 📊 Full-Stack Data Science Lifecycle
* **ETL & Data Engineering:** Mined unstructured web data and nested JSON API endpoints to construct clean, production-ready data frames.
* **Exploratory Analytics & Visualization:** Executed SQL queries and built multi-variate visualizations to isolate key launch outcome drivers.
* **Geospatial & Interactive Systems:** Developed interactive geographic map overlays and reactive dashboard applications for real-time exploratory analysis.

### 🤖 Machine Learning & Stakeholder Reporting
* **Model Optimization & Validation:** Built binary classifiers, handled categorical encodings, scaled feature sets, and executed hyperparameter tuning without data leakage.
* **Executive Presentation:** Translated technical machine learning results, confusion matrices, and ROC curves into actionable bidding strategies against SpaceX.

---

## 🛠️ Production Tech Stack & Ecosystem

| Core Language | Database & ETL | Interactive Dashboards | ML & Analytics | GIS & Mapping |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) | ![Dash](https://img.shields.io/badge/Plotly_Dash-008080?style=flat&logo=plotly&logoColor=white) | ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) | ![Folium](https://img.shields.io/badge/Folium-77B800?style=flat&logo=python&logoColor=white) |
