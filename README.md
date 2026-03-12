# RH-and-wind-speed-project
# RH & Wind HGAM Analysis

## Overview
This project analyzes trends in **relative humidity (RH)** and **maximum wind speed (WS)** over time and space using **Hierarchical Generalized Additive Models (HGAMs)** in R. The analysis explores seasonal patterns, station-level variability, and the effects of vegetation type across multiple weather stations in the U.S. Great Plains from 2010–2019.

The goal is to understand how RH and WS change throughout the year and across locations, using advanced modeling techniques and diagnostics.

This project was done as part of a course assignment
---

## Skills & Tools
- **Programming & Analysis:** R, RMarkdown  
- **Modeling:** HGAMs with `mgcv`, model selection with `MuMIn`  
- **Diagnostics:** Residual checks with `DHARMa`, collinearity checks (VIF)  
- **Data Handling:** Missing value imputation, scaling, tidyverse data manipulation  
- **Visualization:** Faceted plots, heatmaps, and trend predictions  
- **Reproducibility:** Public dataset used directly from source, fully reproducible analysis  

---

## Data
The dataset used in this project (**FireWeather.csv**) was provided as part of course materials and is **publicly available** from the instructor’s GitHub:

https://github.com/LivingLandscapes/Course_EcologicalModeling/master

> The analysis pulls the dataset directly from this source. No raw data is uploaded here, ensuring ethical and reproducible work.

---

## Key Findings
- Vegetation type had minimal effect on RH and WS, while seasonal patterns were highly significant.  
- Temporal smooth terms indicate variability of RH and WS throughout the sampling season, differing across years and vegetation types.  
- Station-level random effects were important, highlighting localized climate variability.  
- Models showed low R² values, reflecting the complex environmental drivers affecting RH and WS.  

> This project demonstrates skills in advanced modeling, reproducible workflow, and effective visualization of environmental datasets.

---

## Notes
- The analysis is based on coursework but modified for clarity and presentation in a portfolio context.  
- All code and figures are included in the PDF for ease of viewing by recruiters or collaborators.
