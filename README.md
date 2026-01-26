# GIS-based analysis of cycling network accessibility and routing scenarios in Graz, Austria.
## Group 1: Fleischhacker Yvonne, Galitschitsch Michael, Koschu Katharina, Lambert David 

## Research Question
How does incorporating risk proxies (traffic speed, tram proximity, slope) change cycling accessibility to universities in Graz compared to pure shortest-distance routing?

## Project Aim
This project analyses cycling accessibility to university locations in Graz using GIS-based network analysis. 

## Study Area
The study area is the city of Graz, Austria. 

## Data
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
- `data/` - raw and processed datasets  
- `notebooks/` - analysis notebooks  
- `maps/` - results
- `.gitignore` 

## Reproducibility
All analyses are reproducible using the provided Python environment. Data sources are openly accessible and processing steps are documented within the repository. 

