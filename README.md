# Geospatial Analysis
This GitHub repository contains data analysis I performed as part of an internship process. The program includes two parts: 

1. **Distance Calculation:** Utilizes multi-processing to efficiently calculate total distances traveled by individuals based on location data, including latitude, longitude, altitude, timestamp, trajectory_id, and individual_id.

2. **Beijing City Travel Map:** Creates a geographical map using OSMnx, GeoPandas, and Folium, focusing on travels made only in Beijing City. The map visualizes the density of travel activities within the city, highlighting areas with higher user engagement.

The repository provides a comprehensive solution for processing and visualizing location-based data efficiently.

Stack:
1. **Core Libraries:** `pandas` and `numpy` for data manipulation, numerical operations, and `math` for mathematical functions.
2. **Geospatial Tools:** `osmnx` and `geopandas` for geospatial data retrieval and manipulation.
3. **Visualization:** `folium` and its plugins for interactive map generation.
4. **Parallel Processing:**  `multiprocessing.Pool` for efficient parallel data processing.
5. **Additional Geometry Handling:** `shapely.geometry` for geometric operations, especially in GeoPandas.
