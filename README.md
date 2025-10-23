# Urban-Heat-Island-UHI-Assessment-in-Lahore-Using-Landsat-8-Thermal-Imagery

# Overview
This project investigates the **Urban Heat Island (UHI)** effect in **Lahore, Pakistan** using **Landsat-8 Collection 2 level-2** satellite imagery and the **Google Earth Engine (GEE)** within Google Colab.

The analysis estimates **Land Surface Temperature (LST)** and **surface indices** such as the **Normalized Difference Vegetation Index (NDVI)** and **Normalized Difference Built-up Index** to understand spatial heat variations across urban and vegetated zones.

# Objectives

- Retrieve and preprocess **Landsat-8 imagery** over Lahore.
- Apply **cloud masking** to remove contaminated pixels
- Compute NDVI and NDBI to identify vegetation and built-up regions.
- Derive Land Surface Temprature (LST) using thermal band B10.
- Visualize spatial patterns and identify **Urban Heat Island Zones**

# Data Source
- Satellite: Landsat-8 (Collection 2, Level-2, SR & TOA)
- Temporal Range: May 1 - September 30, 2024

# Workflow
1. Setup & Authentication
2. Define Region of Interest (ROI)
3. Cloud Masking
4. Image Preparation
5. Index Calculation
6. LST Computation
7. Visualization

# Technologies used
- Google Earth Engine (GEE)
- Python (Colab)
- geemap
- Matplotlib/Seaborn/Pandas
