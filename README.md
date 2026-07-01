# SpaceX Falcon 9 Landing Predictions

IBM Data Science capstone project predicting whether the Falcon 9 first stage will land successfully.

## Project Overview

SpaceX can reduce launch costs when the Falcon 9 first stage lands successfully and can be reused. This capstone project uses public launch data to analyze the factors connected to successful landings and to build classification models that predict first-stage landing outcomes.

The repository contains the full capstone workflow: data collection, web scraping, data wrangling, SQL exploration, visualization, geospatial launch-site analysis, dashboarding, and machine learning prediction.

## Research Question

Can Falcon 9 first-stage landing success be predicted from launch characteristics such as payload mass, orbit, launch site, flight number, and other mission features?

## Workflow

1. Collect launch data from the SpaceX API.
2. Scrape additional launch information from web sources.
3. Filter the data to Falcon 9 launches.
4. Clean missing values and engineer modeling features.
5. Explore relationships among launch site, orbit, payload mass, flight number, and success rate.
6. Analyze launch-site geography with Folium maps.
7. Build an interactive Plotly Dash dashboard.
8. Train and compare machine learning classifiers.
9. Summarize findings in a final capstone report.

## Notebook Map

- `jupyter-labs-spacex-data-collection-api.ipynb` - requests and parses SpaceX API data, filters Falcon 9 launches, and handles missing values.
- `jupyter-labs-webscraping.ipynb` - collects supplementary data through web scraping.
- `labs-jupyter-spacex-Data wrangling.ipynb` - prepares and cleans the combined launch dataset.
- `jupyter-labs-eda-sql-coursera_sqllite.ipynb` - performs SQL-based exploratory analysis.
- `edadataviz.ipynb` - visualizes flight number, launch site, payload mass, orbit, success rate, and yearly launch trends.
- `lab_jupyter_launch_site_location.ipynb` - maps launch sites and nearby geographic features with Folium.
- `SpaceX_Machine Learning Prediction_Part_5.ipynb` - prepares features, standardizes data, and trains classification models for landing success.

## Dashboard

- `spacex_dash_app.py` - interactive dashboard application.
- `Screenshot_dashboard.png` - dashboard preview image.

The dashboard is designed to explore launch outcomes by site and payload range.

## Final Report

- `ds-capstone-ibm-artyom-ashigov.pdf` - final capstone presentation/report.

## Methods

The project combines API requests, web scraping, SQL queries, exploratory visualization, geospatial mapping, dashboarding, and supervised machine learning. The machine learning section uses classification models and compares their predictive performance on landing outcomes.

## Tools

Python, pandas, numpy, requests, BeautifulSoup, SQL, scikit-learn, seaborn, matplotlib, Plotly Dash, Folium, and Jupyter Notebook.
