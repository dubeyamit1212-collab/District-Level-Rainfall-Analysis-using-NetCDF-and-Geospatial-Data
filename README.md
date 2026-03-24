# District-Level Rainfall Analysis using NetCDF & Geospatial Data

This project performs geospatial rainfall analysis using NetCDF data with Xarray, GeoPandas, and Rioxarray.

---

## Overview

The project focuses on analyzing rainfall patterns over Maharashtra using satellite-based gridded data. It includes district-level aggregation, time-series analysis, and advanced area-weighted computations.

---

## Features

-  NetCDF rainfall data processing using Xarray  
-  Spatial clipping using GeoPandas & Rioxarray  
- District-wise rainfall analysis (Maharashtra)  
- Time-series analysis (Pune district)  
- Area-weighted rainfall using cosine latitude weighting  
-  Pixel-wise fractional rainfall estimation using geometry intersection  

---

## Tech Stack

- Python  
- Xarray  
- GeoPandas  
- Rioxarray  
- Matplotlib  
- Shapely  

---

## Key Insights

- Rainfall varies significantly across districts  
- Monsoon months (June–September) dominate total rainfall  
- Weighted rainfall provides more realistic spatial estimates  
- Fractional pixel method improves accuracy near boundaries  

---

##  How to Run

```bash
pip install xarray geopandas rioxarray matplotlib shapely
