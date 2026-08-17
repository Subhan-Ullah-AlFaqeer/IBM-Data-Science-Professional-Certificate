# 🗺️ Module 3: Interactive Visual Analytics with Folium Maps & Plotly Dash

Welcome to the third module of the **Applied Data Science Capstone**! In this module, we step beyond static data visualization to build fully interactive visual tools. We utilize **Folium** to construct spatial maps that analyze launch site proximity to key geographical markers (railways, highways, coastlines) and deploy an interactive **Plotly Dash** web application to explore flight outcomes dynamically.

---

## 📝 Core Technical Objectives
* **Geospatial Proximity Analysis:** Building interactive map overlays with `Folium` to measure distances between launch sites, coastlines, and transport infrastructure.
* **Geographic Outcome Clustering:** Utilizing `MarkerCluster` objects to group launch points dynamically and visualize regional success/failure densities.
* **Interactive Dashboard Engineering:** Developing a reactive `Plotly Dash` web application (`spacx_dash.py`) with dropdown filters and range sliders for real-time analytics.

---

## 🧪 Interactive Laboratory & Visual Selection Matrix

This module's core lab deliverables, interactive scripts, and geospatial assets are mapped directly to their targeted operational steps:

| Notebook / Script / Asset | Integrated Frameworks | Primary Analytical Focus |
| :--- | :--- | :--- |
| **[Lab 1: Spatial Proximity Analysis](./01_lab-jupyter-launch-site-location-v2.ipynb)**<br>*(Data: `spacex_launch_geo.csv`)* | • Folium<br>• MarkerCluster<br>• Haversine Distance | Plotting launch pad coordinates, clustering launch outcomes, and calculating distances to nearby coastlines, railways, and cities. |
| **[App Script: Plotly Dash Application](./spacx_dash.py)**<br>*(Manual: `02_Build_a_Dashboard_Application_with_Plotly_Dash.pdf`)* | • Plotly Dash<br>• Dash Core/HTML<br>• Plotly Express | Building a web dashboard featuring dynamic pie charts for site success rates and payload vs. landing success scatter plots. |

---

## 💡 Visual Pipeline Reference

Geospatial and interactive dashboard operations mapped systematically by diagnostic requirements:

* **Regional Launch Site Mapping** ➔ Rendered via **Folium Tile Maps** centered on geographical coordinates (`Latitude`, `Longitude`).
* **Dense Coordinate Grouping** ➔ Managed via **Folium MarkerClusters** to clean dense clusters of historical launch points.
* **Geospatial Safety Distance Checks** ➔ Calculated via **Haversine Distance Formulas** to quantify safety buffers from population centers and infrastructure.
* **Reactive Payload-Success Analytics** ➔ Rendered via **Plotly Dash Callbacks** to update visualizations dynamically based on user controls.

---

## 🎯 Technical Skills Architecture

### 🗺️ Geospatial Analytics (Folium)
* **Custom Coordinate Markers:** Custom-built interactive map markers displaying launch site names, landing outcomes, and payload details on click.
* **Distance Computation:** Programmed geodesic calculation utilities to measure spatial proximity to major transport arteries and safety margins.
* **Spatial Clustering:** Applied `MarkerCluster` layers to handle multiple overlapping launches per launch pad cleanly.

### 📊 Interactive Dashboard Development (Plotly Dash)
* **Reactive Callback Architecture:** Configured `@app.callback` decorators to connect interactive UI inputs directly to chart rendering functions.
* **Dynamic Site-Selection Controls:** Built dropdown menus allowing users to toggle between overall launch success ratios and single-site breakdowns.
* **Payload Mass Range Sliders:** Integrated multi-point range sliders to filter payload masses ($0 - 10,000\text{ kg}$) and observe real-time impact on landing outcomes.

---

## 🛠️ Production Tech Stack & Ecosystem

| Programming Language | Interactive Web Framework | Geospatial Engine | Data Processing | Environment |
| :---: | :---: | :---: | :---: | :---: |
| ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) | ![Dash](https://img.shields.io/badge/Plotly_Dash-008080?style=flat&logo=plotly&logoColor=white) | ![Folium](https://img.shields.io/badge/Folium-77B800?style=flat&logo=python&logoColor=white) | ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) | ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white) |
