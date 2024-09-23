# Random Forest Classification with LANDSAT 8

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter%20Notebook-6.0%2B-orange.svg?logo=jupyter&logoColor=white)
![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-Ready-green.svg?logo=googleearth&logoColor=white)
![Folium](https://img.shields.io/badge/Folium-0.12.1%2B-red.svg?logo=folium&logoColor=white)
![Geemap](https://img.shields.io/badge/Geemap-0.9.0%2B-purple.svg?logo=geemap&logoColor=white)


This Jupyter notebook demonstrates the process of performing Random Forest classification using LANDSAT 8 satellite imagery. The analysis leverages Google Earth Engine (GEE) for data processing and visualization, incorporating the FOLIUM library and Geemap for interactive mapping.

## Table of Contents

1. [Initializing Earth Engine and Import Libraries](#initializing-earth-engine-and-import-libraries)
2. [Define a Region of Interest](#define-a-region-of-interest)
3. [Load LANDSAT 8 Data](#load-landsat-8-data)
4. [Classification Model](#classification-model)
5. [FOLIUM App](#folium-app)
6. [Geemap](#geemap)

## Notebook Overview

>### 1. Initializing Earth Engine and Import Libraries
>- Set up the Google Earth Engine environment.
>- Import necessary libraries for data manipulation and visualization.
>### 2. Define a Region of Interest
>- Specify the geographic area for analysis using coordinates or a shapefile.
>### 3. Load LANDSAT 8 Data
>- Access and load relevant LANDSAT 8 imagery from Google Earth Engine.
>### 4. Classification Model
>- Implement a Random Forest classification model on the loaded LANDSAT data.
>- Evaluate the model's performance and visualize the results.
>### 5. FOLIUM App
>- Create an interactive web map using the FOLIUM library to display classified results.
>### 6. Geemap
>- Utilize Geemap for advanced mapping capabilities to enhance visualizations of the results.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Google Earth Engine account
- Required libraries (e.g., `geemap`, `folium`, `numpy`)

## How to Run the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/arnabsaha7/SmartGeoMapping.git
   cd SmartGeoMapping
   ```

2. Install the required libraries (if not already installed):
   ```bash
   pip install geemap folium numpy 
   ```

3. Open the Jupyter notebook:
   ```bash
   jupyter notebook RF_Classification_with_LANDSAT_8.ipynb
   ```

4. Follow the instructions in the notebook to execute each section.

## Visualizations

Here are some visual outputs generated from the analysis:

<p align="center">
  <div style="display:inline-block; margin:10px; text-align:center;">
    <img src="maps/original.png" alt="Original LANDSAT Image" height="200"/>
    <div>Original LANDSAT Image</div>
  </div>
  <div style="display:inline-block; margin:10px; text-align:center;">
    <img src="maps/landsat.png" alt="LANDSAT 8 Data" height="200"/>
    <div>LANDSAT 8 Data</div>
  </div>
  <div style="display:inline-block; margin:10px; text-align:center;">
    <img src="maps/classification.png" alt="Classification Result" height="200"/>
    <div>Classification Result</div>
  </div>
</p>


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Earth Engine team
- LANDSAT data providers
- Contributors to the libraries used


---
For any inquiries or contributions, feel free to reach out!