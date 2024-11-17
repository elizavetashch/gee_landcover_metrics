# Land cover metrics calculation in Google Earth Engine (GEE) 

Hi! 
This repository contains GEE codes, R codes and directions to calculate land cover metrics in google earth engine. 
It is user firendly and easy to customize, so if you want 
 - to calculate area of land cover classes within a specific buffer
 - to calcuate edge of each class within a specific buffer
 - to calculate shannons diversity, simpsons evennes index, richness or perimeter to area ratio within a specific buffer

then this repository is what you were looking for!

## Contents 
- gee_codes
- R_codes

## Links to GEE Codes: 
- **Maps and Edge Visualization** 🗺️
  
  A GEE code for land cover map visualization and edge detection of land cover classes.
  
  Link: [GEE maps_and_edge_visualisation](https://code.earthengine.google.com/c2709949d2d31c7cf6f1735a82781643)
- **Land Cover Metrics Calculation** 🧮
  
  A GEE code for calculating land cover metrics (area in m² and edge length in m) from a given dataset (CSV file) and land cover maps.
  
  Link: [GEE landcover_metrics_calculation](https://code.earthengine.google.com/3d97c3bb1580aa7b24778c0ff61d00bd)

## Description: 
- **Maps and Edge Visualization**
  
  This GEE code visualizes land cover maps (sourced from [awesome-gee-community-catalog](https://gee-community-catalog.org/projects/glc_fcs/)) and displays edge detections for each land cover class. 
- **Land Cover Metrics Calculation**
  
  This GEE code calculates land cover metrics, including the area (in square meters) and edge length (in meters), based on a provided dataset (CSV file) and land cover maps.

_**Note**:_  
🎨 _Land Cover Metrics Calculation is customizable. Lines where customization is possible are marked with comments starting with //customize:_.  

💾 _Both codes come with a dummy dataset and are designed for you to run and explore on your system._

## Customization: 
If you're new to Google Earth Engine (GEE) and need to customize the code, here are some tips:

- **comments** are in green  🟢
- **numbers** are in blue 🔵 
- **strings** are in red 🔴 
- **code** structure is in black ⚫
- **functions** are in violet 🟣

**Important**: Only modify 🔴 **RED** and 🔵 **BLUE** elements to tailor the code to your dataset or requirements.
