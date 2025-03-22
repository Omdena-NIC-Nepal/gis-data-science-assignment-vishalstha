# GIS Data Science Assignment

## Objective

This project explores administrative boundary and climate data for Nepal using GIS and data science techniques. The goal is to analyze temperature trends, visualize spatial data, and derive insights and trends of climate change in nepal over time.

## Assignment Tasks

1. Data Collection: Import data from github repository and process vector and raster climate data.

2. Data Preprocessing: Check for missing values, Standardize Coordinate Reference Systems (CRS) and clean datasets.

3. Data Visualization: Generate maps and visualizations to represent climate trends in Nepal.

4. Exploratory Data Analysis (EDA): Analyze spatial data and Visualize, spatial data,temperature & Precipitation variations.

## Dataset and Preprocessing

### Source:

- GIS data includes administrative boundaries, rivers, glaciers, and temperature & precipitation (2020 and 2050) information.

### Preprocessing Steps:

- Read vector (shapefiles) and raster (grid-based) data.

- Verify and convert CRS to ensure all datasets align spatially.

- Extract and clean relevant data for visualization.

## Environment Setup

To run the notebook, import the required libraries:

```
import numpy as np
import pandas as pd
import geopandas as gpd
import matplotlib.pyplot as plt
import seaborn as sns
import rasterio
from rasterio.plot import show
```

## Data Visualization

The following visualizations were produced to analyze climate data for Nepal:

- Administrative Boundary Map: Displays Nepal’s district and province boundaries.

- River and Glacier Map: Shows major water bodies and glaciers in Nepal.

- Temperature and Precipitation Trend Over Time: Visualization showing temperature and precipitation trend over years.

- Temperature and Precipitation Trend Over Map of Nepal: Overlay visualization of temperature and precipitation trend over years in Map of Nepal.

## Findings from EDA

#### Administrative, Rivers and Glaciers Analysis Numeric Finding

- Number of Provinces: 7
- Number of Districts: 77
- Number of Local Bodies/Governments: 755
- No. of Rivers in Nepal: 4
- No. of Glaciers in Nepal: 20
- Total Flow of water in river in 2020: 6800
- Total Flow of water in river in 2050: 6100
- Average Flow of water in river in 2020: 1700.0
- Average Flow of water in river in 2050: 1525.0

#### Data Visualization Finding

- Water flow in rivers shows that flow of water is likely to decrease over time in Nepal
- Precipitation visualization shows that rainfall is likely to decrease over time until the year 2050 compared to 2020
- No further conclusions could be drawn as the dataset includes only visualization data without detailed numerical analysis

## Conclusion

This project provides insights into Nepal’s climate trends using GIS and data science. The findings are based on visualization data, and further analysis with a more comprehensive dataset would be needed for deeper climate modeling and insight recommendations.
