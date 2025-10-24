# SpaceX Capstone Project

## Overview
This project analyzes SpaceX launch data using Python, SQL, and data visualization techniques. It covers the complete data science workflow: data collection, wrangling, exploratory data analysis, interactive visualization, and predictive modeling. The project also includes an interactive dashboard built using Plotly Dash and map visualizations with Folium.

## Project Objectives
- Analyze SpaceX launch data to understand success/failure patterns.
- Explore relationships between payload, booster version, and launch outcome.
- Perform predictive analysis using classification models to predict launch success.
- Build interactive visualizations and dashboards for better insights.

## Repository Structure
```
spacex-capstone/
├── notebooks/          # Jupyter notebooks for each step
│   ├── 01-Spacex-Data-Collection-API.ipynb
│   ├── 02-Spacex-Web-Scraping.ipynb
│   ├── 03-Spacex-Data-Wrangling.ipynb
│   ├── 04-Spacex-EDA-SQL.ipynb
│   ├── 05-Spacex-EDA-Visualization.ipynb
│   ├── 06-Spacex-Generating-Maps.ipynb
│   ├── 07-Spacex-Launch-Site-Location.ipynb
│   └── 08-Spacex-Machine-Learning-Prediction.ipynb
├── datasets/           # CSV datasets used for analysis
│   ├── dataset_part_2.csv
│   ├── dataset_part_3.csv
│   └── spacex_launch_dash.csv
├── dash_app/           # Plotly Dash interactive dashboard
│   └── spacex-dash-app.py
├── presentation/       # Final PowerPoint presentation
│   └── ds-capstone.pptx
|   └── ds-capstone.pdf
└── README.md
```

## Python Libraries Used
- Data Manipulation: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`, `plotly`
- Interactive Maps: `folium`
- Machine Learning: `scikit-learn`
- SQL: `sqlite3`

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/mohanpsivam/spacex-capstone.git
cd spacex-capstone
```
2. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn plotly folium scikit-learn
```
3. Open the Jupyter notebooks from the `notebooks/` folder.
4. Run the Dash app:
```bash
python dash_app/spacex-dash-app.py
```
Then open your browser at `http://127.0.0.1:8050/`.

## GitHub Links for Peer Review
- [Data Collection Notebook](notebooks/01-Spacex-Data-Collection-API.ipynb)
- [Data Wrangling Notebook](notebooks/03-Spacex-Data-Wrangling.ipynb)
- [EDA with SQL Notebook](notebooks/04-Spacex-EDA-SQL.ipynb)
- [EDA with Visualization Notebook](notebooks/05-Spacex-EDA-Visualization.ipynb)
- [Folium Map Notebook](notebooks/06-Spacex-Generating-Maps.ipynb)
- [Launch Site Location Notebook](notebooks/07-Spacex-Launch-Site-Location.ipynb)
- [Predictive Analysis Notebook](notebooks/08-Spacex-Machine-Learning-Prediction.ipynb)
- [Dash App Script](dash_app/spacex-dash-app.py)

## License
This project is for educational purposes


