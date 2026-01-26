# final-project-group1-cycling-network
GIS-based analysis of cycling network accessibility and routing scenarios in Graz, Austria.

## Project Aim
(Planned:) This project investigates cycling network accessibility and routing scenarios
in Graz, Austria, using open GIS data and Python-based network analysis.

## Study Area
City of Graz, Austria.

## Data
- OpenStreetMap (street network, cycling infrastructure)
- Open DEM data (slope calculation)
- Administrative boundaries (open data sources)

## Environment
The analysis was conducted using Python 3.12 in a virtual environment
(`venv-gst200b`). Required libraries include osmnx, geopandas, networkx and pandas.


## Methods (planned)
- Network extraction using OSMnx
- Speed and impedance modelling
- Scenario-based routing analysis
- GIS-based accessibility assessment

## Repository Structure
- `data/` – raw and processed datasets  
- `notebooks/` – analysis notebooks  
- `src/` – reusable Python functions (maybe?)  
- `outputs/` – maps, figures, tables

## Reproducibility
All analyses are reproducible using the provided Python environment.
