# Transportation-Energy-Vunerability
## File Description    
**Transportation energy vulnerability analysis at census tract level**
1. Shapefiles
The shapefiles in **census_shp** are for census tracts.  
The shapefiles in **state_shp** are for states.
2. Data for census tracts
All of the data are in folder named census_data.   
**exposure_census.csv** is the file including the exposure score named min_max_ex.
**sensitivity_census.csv** is the file including the sensitivity score named min_max_sens.
**adaptive_capacity_census.csv** is the file including the adaptive capacity score named min_max_ac.     
    
**Cities energy vulnerability analysis at census tract level**
1. Shapefiles
All of the shapefiles for each city (i.e., New York, Los Angeles, Chicago) are in the folder named **Basemap** in each city's folder.
2. Data for census tracts
**la_all_census.csv, chi_all_census.csv, ny_all_census.csv** include the exposure, sensitivity, adaptive capacity, multiplicative/additive vulnerability in New York, Los Angeles, Chicago.

**EV adoption in IL**
1. Shapefiles
The shapefiles in **IL_county_shp** are for counties in IL.   
2. Data
The vulnerability scores at county level in IL are in **vul_score CV-EV.xlsx**.
     
## Codes
All of the codes for static maps are in **USA.ipynb**.    
Folium maps are in **Folium map.ipynb**.
