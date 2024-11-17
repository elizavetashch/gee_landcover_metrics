# Land Cover Metrics Calculation in Google Earth Engine🌍

This repository contains GEE codes, R scripts, and directions to calculate land cover metrics in Google Earth Engine. It is user-friendly and easy to customize. If you want to:

- Calculate the area of land cover classes within a specific buffer
- Calculate the edge of each class within a specific buffer
- Calculate Shannon's diversity index, Simpson's evenness index, richness, or perimeter-to-area ratio within a specific buffer

Then this repository is what you’ve been looking for! 🌟

## Contents
- **gee_code** 📁  
  Contains two GEE code files and one markdown file with directions.
  
- **R_code** 📁  
  Contains two R code files and one markdown file with directions.
  
- **Handout** 📄  
  This PDF file contains the presentation slides I presented during the workshop I organized on November 12, 2024, within the Computational Landscape Department at UFZ Leipzig, as part of a project supervised by Elina Takola.

## GEE Code Description:
### Links to GEE Codes:
- **Maps and Edge Visualization** 🗺️  
  A GEE code for land cover map visualization and edge detection of land cover classes.  
  [GEE maps_and_edge_visualisation](https://code.earthengine.google.com/c2709949d2d31c7cf6f1735a82781643)

- **Land Cover Metrics Calculation** 🧮  
  A GEE code for calculating land cover metrics (area in m² and edge length in m) from a given dataset (CSV file) and land cover maps.  
  [GEE landcover_metrics_calculation](https://code.earthengine.google.com/3d97c3bb1580aa7b24778c0ff61d00bd)

### Description:
- **Maps and Edge Visualization**  
  This GEE code visualizes land cover maps (sourced from [awesome-gee-community-catalog](https://gee-community-catalog.org/projects/glc_fcs/)) and displays edge detections for each land cover class.

- **Land Cover Metrics Calculation**  
  This GEE code calculates land cover metrics, including area (in square meters) and edge length (in meters), based on a provided dataset (CSV file) and land cover maps.

_**Note**:_  
🎨 _The Land Cover Metrics Calculation is customizable. Lines where customization is possible are marked with comments starting with `//customize:`._  

💾 _Both codes come with a dummy dataset and are designed for you to run and explore on your system._

### Customization:  
If you're new to Google Earth Engine (GEE) and need to customize the code, here are some tips:

- **comments** are in green  🟢
- **numbers** are in blue 🔵
- **strings** are in red 🔴
- **code** structure is in black ⚫
- **functions** are in violet 🟣

**Important**: Only modify 🔴 **RED** and 🔵 **BLUE** elements to tailor the code to your dataset or requirements.

## R Code Description:
### R Codes
- **merge_csv_outputs**  
This R script merges all CSV outputs from GEE into a single file and creates a `buffer_radius` column, assigning the buffer radius for each CSV file.  
_**Note**:_ You need to adjust the buffer radius values to match those used in your specific dataset.

- **R_calculate_landcover_metrics**  
This R script calculates land cover diversity indices based on the area and edge of land cover classes. It requires only the `tidyr` and `dplyr` packages. Optionally, you can use the `diversity()` function from the **vegan** package to calculate the diversity indices.

**General Note:**  
These R scripts are intended as guidelines rather than fully reproducible solutions. **Please adjust them to suit your specific needs and dataset.**
