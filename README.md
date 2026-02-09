# My First Geospatial Analysis Project 🌍

## Project Overview
This project demonstrates basic geospatial analysis techniques using Python. The goal is to analyze healthcare facility accessibility in a sample region.

## Project Structure
my-first-geo-project/
├── data/ # Data directory
│ ├── raw/ # Original, immutable data
│ ├── processed/ # Cleaned, transformed data
│ └── samples/ # Small sample datasets for testing
├── src/ # Source code
│ ├── analysis/ # Analysis scripts
│ └── utils/ # Utility functions
├── notebooks/ # Jupyter notebooks for exploration
├── docs/ # Documentation
├── reports/ # Generated reports
├── figures/ # Output visualizations
├── .gitignore # Git ignore file
└── README.md # This file

text

## Objectives
1. Map healthcare facilities in a sample area
2. Calculate population access to nearest facilities
3. Identify underserved areas
4. Generate accessibility heatmaps

## Technologies Used
- **Python 3.8+**
- **Geospatial Libraries:**
  - GeoPandas
  - Rasterio
  - Fiona
  - Shapely
  - Contextily (basemaps)
- **Visualization:**
  - Matplotlib
  - Seaborn
  - Folium (interactive maps)
- **Analysis:**
  - NetworkX (for routing)
  - Scikit-learn (for clustering)

## Data Sources
- Health facilities: [Healthsites.io](https://healthsites.io/)
- Population data: [WorldPop](https://www.worldpop.org/)
- Administrative boundaries: [GADM](https://gadm.org/)
