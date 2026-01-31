# GIS-based analysis of cycling network accessibility and routing scenarios in Graz, Austria.

Graz is characterized by relatively short urban distances, making cycling an attractive option for everyday mobility. However, cycling comfort and safety are not evenly distributed across the city. Factors such as slope, high traffic speeds, and tram infrastructure can significantly reduce cycling quality, even in areas close to university campuses.

This project therefore analyzes bicycle accessibility to eight major university locations in Graz. Beyond network distance, the analysis incorporates expected cycling effort by considering risk proxies such as slope, traffic speed, and proximity to tram tracks. The results highlight that short distances in Graz do not necessarily correspond to safe, comfortable, or attractive cycling conditions.

## Research Question
How does incorporating risk proxies (traffic speed, tram proximity, slope) change cycling accessibility to universities in Graz compared to pure shortest-distance routing?

## Data Sources
The analysis is based on different geospatial datasets:
- OSM (bike and tram network, university locations, city boundary/districts)
- GIS Steiermark (1 m DEM) 

## Environment
The analysis was coded using Python 3.12 and 3.11 within a virtual environment (venv-gst200b).

## Methods
The workflow consists of the following steps:
- Data provision and collection
- Preprocessing of spatial data and network preparation
- Analysis, including routing, accessibility analysis, grid-based analysis, and statistical and comparative evaluation
- Visualisation of results

## Repository Structure
final-project-group1-cycling-network
│
├── data/
│   └── processed/                 # Cleaned and processed datasets
│
├── notebooks/
│   ├── figure/                    # Exported data/map visualizations
│   ├── maps/                      # Exported Kepler map visualizations
│   └── final-project-gr1.ipynb    # Main analysis notebook
│
├── .gitignore                     # Git ignore rules
├── LICENSE                        # Project license
└── README.md                      # Project overview

## Requirements
osmnx
geopandas
networkx
pandas
keplergl
numpy
matplotlib
shapely
scipy
rasterio

## Reproducibility
All analyses are reproducible using the provided Python environment. Data sources are openly accessible and processing steps are documented within the repository. 

