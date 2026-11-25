# CISC7204 Assignment 02 — Data Preprocessing & Visualization Labs

**Author:** Sun Yuanjiao (MC65343), University of Macau
**Course:** CISC7204 — Assignment 02

This repository collects the completed lab notebooks and supporting data files for
Assignment 02. The labs cover pandas-based data preprocessing, statistical exploratory
analysis, line plots and comparisons, and geospatial (choropleth) visualization.

## Topics Covered

- Dataset preprocessing and exploration with pandas (series, DataFrames, indexing)
- Matplotlib line charts: trend extraction, labels, annotations, multi-series comparison
- Statistical and distribution analysis
- Choropleth maps using country- and US-state-level GeoJSON data
- Lab screenshot records for the plotting exercises

## Repository Structure

```
cisc7204-assignment-02/
├── README.md
├── module1/   # Lab01 pandas preprocessing; Lab02 matplotlib line plots (+ Lab02_screenshots/)
├── module2/   # Lab01–Lab03 visualization labs
├── module3/   # Lab01–Lab02 geospatial analysis; world_countries.json
├── module4/   # Lab01 visualization lab
└── module5/   # Practice Lab01 and Final Lab01; us-states.json
```

## Datasets and Resources

- The CSV/JSON files stored alongside the notebooks are public course datasets and GeoJSON
  boundary files used for the visualization exercises.
- `module1/Lab02_screenshots/` records the plotting steps and resulting charts for Lab02.
- All files are de-identified public course material. No passwords, API keys, personal data or
  restricted datasets are included in this repository.

## How to Run

1. Install Python 3 and the required packages (pandas, NumPy, Matplotlib, Seaborn, Folium /
   Plotly as used in the notebooks).
2. Open the notebook in the matching `moduleX/` folder with Jupyter Notebook or JupyterLab.
3. Run the cells in order; the CSV/JSON datasets are stored alongside the notebooks.

## Tools

Python, pandas, NumPy, Matplotlib, Seaborn, Folium/Plotly (choropleth maps), Jupyter Notebooks
