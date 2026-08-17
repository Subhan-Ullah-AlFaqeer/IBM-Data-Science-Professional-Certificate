# 🚀 Module 1: Data Collection, Web Scraping, & Data Wrangling

Welcome to the first module of the **Applied Data Science Capstone**! In this capstone project, we predict whether the SpaceX Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches at $62 million—compared to upwards of $165 million for other providers—largely because the first stage is reusable. Determining landing success unlocks precise launch cost estimations, enabling competitive bidding analysis.

---

## 📝 Core Technical Objectives
* **API Data Extraction:** Interfacing with the SpaceX REST API to extract raw telemetry data, flight metrics, and core payload parameters into structured JSON formats.
* **Web Scraping Pipelines:** Utilizing `BeautifulSoup` to parse HTML launch logs directly from Wikipedia to supplement historical data.
* **Data Wrangling & Cleaning:** Normalizing nested JSON payloads, engineering binary target landing outcomes (`0` or `1`), and handling missing values using Pandas.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core lab deliverables and data extraction scripts are mapped directly to their targeted operational steps:

| Notebook Pipeline | Integrated Frameworks | Primary Analytical Focus |
| :--- | :--- | :--- |
| **[Lab 1: SpaceX REST API Mining](./01_jupyter-labs-spacex-data-collection-api-v2.ipynb)** | • Requests<br>• Pandas<br>• JSON Engine | Extracting raw launch records from the SpaceX API, unnesting complex payload fields, and creating the primary dataset. |
| **[Lab 2: Wikipedia Web Scraping](./02_jupyter-labs-webscraping.ipynb)** | • BeautifulSoup4<br>• HTML Parser<br>• Regex | Scraping historical Falcon 9 launch tables from Wikipedia to extract launch site coordinates and core payload masses. |
| **[Lab 3: Feature Engineering & Wrangling](./03_labs-jupyter-spacex-Data%20wrangling-v2.ipynb)** | • Pandas<br>• NumPy | Cleaning payload values, analyzing launch site landing rates, and creating the binary target variable (`Class`). |

---

## 💡 Visual Pipeline Reference

Data engineering operations mapped systematically by diagnostic requirements:

* **API Payload Structuring** ➔ Processed via **JSON Normalization** to expand nested dictionary fields into tabular data frames.
* **Unstructured Web Scraping** ➔ Extracted via **BeautifulSoup HTML Parsing** to convert raw table rows into clean metrics.
* **Landing Outcome Mapping** ➔ Deployed via **Pandas Categorical Encoding** to convert complex landing states into a binary `Class` target.
* **Missing Value Imputation** ➔ Managed via **Mean Value Imputation** to handle null payload mass entries safely.

---

## 🎯 Technical Skills Architecture

### 📊 Data Collection & ETL
* **REST API Ingestion:** Built custom payload query loops to extract stage metrics, launch sites, orbit types, and landing pad telemetries.
* **HTML Parsing & Regex Extraction:** Scripted automated scraping scripts to clean table structures and remove formatting noise from scraped rows.
* **Target Feature Formulation:** Classified landing outcomes (e.g., `True ASDS`, `False Ocean`, `None Ground`) to construct the predictive binary target (`Class`).

### 🛠️ Production Data Wrangling
* **DataFrame Structuring:** Transformed multi-nested dictionaries into structured 2D Pandas DataFrames for downstream analytics.
* **Data Cleansing Pipelines:** Imputed missing values for numerical features ($PayloadMass$) and removed duplicate launch logs.
* **Version Control Integration:** Established a structured Git directory workflow for sharing and documenting Jupyter notebook artifacts.

---

## 🛠️ Production Tech Stack & Ecosystem

| Programming Language | Ingestion Engine | Web Scraping | Data Processing | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![Requests](https://img.shields.io/badge/Requests-3776AB?style=flat&logo=python&logoColor=white) | ![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup4-00599C?style=flat&logo=python&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
