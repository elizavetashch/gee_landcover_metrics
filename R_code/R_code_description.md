## R Codes

- **merge_csv_outputs**  
This R script merges all CSV outputs from GEE into a single file and creates a `buffer_radius` column, assigning the buffer radius for each CSV file.
_**Note**: You need to adjust the buffer radius values to match those used in your specific dataset._


- **R_calculate_landcover_metrics**  
This R script calculates land cover diversity indices based on the area and edge of land cover classes. It requires only the `tidyr` and `dplyr` packages. Optionally, you can use the `diversity()` function from the **vegan** package to calculate additional indices.  


### **General Note**  
These R scripts are intended as guidelines rather than fully reproducible solutions. **Please adjust them to suit your specific needs and dataset.**
