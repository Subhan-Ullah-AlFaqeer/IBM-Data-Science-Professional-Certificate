# 🔍 Module 2: Exploratory Data Analysis (EDA) with SQL & Data Visualization

Welcome to the second module of the **Applied Data Science Capstone**! Having collected and wrangled the raw SpaceX dataset, this module focuses on extracting deeper operational insights using SQL database queries and statistical data visualizations. 

By analyzing the relationships between launch sites, payload masses, orbit types, and landing outcomes, we uncover key trends that directly inform our predictive modeling strategy.

---

## 📝 Core Technical Objectives
* **SQL Telemetry Analysis:** Executing relational SQL queries against the SpaceX database (`my_data1.db`) to filter, aggregate, and analyze launch variables.
* **Exploratory Visual Analytics:** Utilizing Seaborn and Matplotlib to construct multi-variate scatter plots, bar charts, and trajectory trendlines.
* **Flight Feature Correlation:** Isolating how payload weights, orbit selections (e.g., LEO, GTO, ISS), and launch sites impact the first-stage landing success rate (`Class`).

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core lab deliverables and database engines are mapped directly to their targeted operational steps:

| Notebook / Database Pipeline | Integrated Frameworks | Primary Analytical Focus |
| :--- | :--- | :--- |
| **[Lab 1: SQL Data Analysis](./01_jupyter-labs-eda-sql-coursera_sqllite.ipynb)**<br>*(Database: `my_data1.db`)* | • SQLite3<br>• SQL Alchemy<br>• Pandas SQL Interface | Writing SQL queries to calculate total payload masses, list unique launch sites, filter failed landings, and analyze success rates by date ranges. |
| **[Lab 2: Visual Data Analysis](./02_jupyter-labs-eda-dataviz-v2.ipynb)** | • Seaborn<br>• Matplotlib<br>• Pandas | Plotting flight numbers against payload mass, mapping orbit types to landing success rates, and visualizing long-term launch site usage trends. |

---

## 💡 Visual Pipeline Reference

Exploratory analytics operations mapped systematically by diagnostic requirements:

* **Categorical Success Comparison** ➔ Deployed via **Bar Charts** to compare landing success percentages across different orbit types.
* **Payload vs. Outcome Clustering** ➔ Deployed via **Scatter Plots** to identify payload weight boundaries affecting landing success.
* **Launch Site Flight Trajectories** ➔ Deployed via **Categorical Swarm/Scatter Plots** to track launch site frequency over time.
* **Database Aggregation & Filtering** ➔ Executed via **SQL Queries (`GROUP BY`, `WHERE`, `ORDER BY`)** for precise numerical summaries.

---

## 🎯 Technical Skills Architecture

### 🗄️ Relational Database Management (SQL)
* **Aggregations & Filtering:** Formulated SQL statements to compute total/average payload masses and identify specific landing outcome distributions.
* **Temporal Querying:** Executed time-bounded queries to analyze how Falcon 9 landing reliability evolved over successive launch years.
* **Database Interfacing:** Utilized `sqlite3` and Pandas SQL abstractions to query embedded database instances directly within Jupyter environments.

### 📊 Exploratory Visual Analytics
* **Multi-Variate Plotting:** Programmed hue-encoded scatter plots to evaluate relationships between three variables simultaneously ($FlightNumber$, $PayloadMass$, $Class$).
* **Orbit Success Rate Auditing:** Dissected success rates across GTO, LEO, HEO, and ISS orbits to identify high-risk launch trajectories.
* **Trend Analysis:** Mapped annual success trends to visualize SpaceX's operational learning curve and stage recovery improvements.

---

## 🛠️ Production Tech Stack & Ecosystem

| Programming Language | Database Engine | Data Processor | Visualization Core | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) | ![Seaborn](https://img.shields.io/badge/Seaborn-4E73DF?style=flat&logo=pandas&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
