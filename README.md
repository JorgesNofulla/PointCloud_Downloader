# Code Documentation: Interactive Map for Geo Data Handling

## Overview
This repository presents a Python script designed to interactively select geographic areas on a map, identify intersecting geospatial data, and download corresponding files based on user input from Geotiles.nl, AHN 4 files.

## Key Features
Interactive Map Interface: Utilizes ipyleaflet for map rendering and user interaction.
Coordinate Transformation: Implements pyproj for converting geographic coordinates.
Data Filtering and Clipping: Uses geopandas and shapely to manipulate and query geospatial data, and laspy to clip point cloud data within the selected polygon.
File Download and Handling: Uses requests to download files based on user-selected areas and pathlib for directory management.
User Interaction: Leverages ipywidgets for dynamic user input handling and feedback.

## Environment
Python Version: 3.11.9
Required Libraries: ipyleaflet, pyproj, ipywidgets, geopandas, shapely, requests, laspy, numpy, pathlib

## MADNATORY FILE
Link to download the list of AHN tiles:
https://static.fwrite.org/2023/01/AHN_subunits_GeoTiles.zip

## Example how it works:

1. Zoom into your area of choice  
2. Draw a polygon, exactly the area and shape you want  
3. Click cancel to redraw or confirm to start the process


![image](https://github.com/user-attachments/assets/e2e4ae22-50fa-403f-a81b-d90d8c145273)


## Output example in PointCloud :

![image](https://github.com/user-attachments/assets/518ba049-2092-4591-8ce2-94f2b310ffa8)



## Author
Name: Jorges Nofulla
Contact: jorgesnofulla12@gmail.com
