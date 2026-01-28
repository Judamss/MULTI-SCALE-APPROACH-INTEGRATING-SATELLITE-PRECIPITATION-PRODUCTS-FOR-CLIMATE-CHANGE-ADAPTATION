# MULTI-SCALE-APPROACH-INTEGRATING-SATELLITE-PRECIPITATION-PRODUCTS-FOR-CLIMATE-CHANGE-ADAPTATION
Hydro-Climate Drought Analysis Framework
This repository contains the core computational methodology developed during my PhD thesis: "Current Assessment and Future Projections of Drought in the Tensift Watershed, Morocco" (Defended Jan 2026). 

Overview
This Python framework implements a multi-source approach for hydrological drought monitoring and climate projection. It is designed for topographically complex, semi-arid regions where ground observations are sparse. 

Key Features

Satellite Data Evaluation: Scripts to validate PERSIANN-CCS-CDR and ERA5 datasets against in-situ gauge data using statistical metrics (CC, RMSE, NSE, PBIAS). 


Elevation-Stratified Bias Correction: A novel integration method using a 500m topographic threshold to merge CNRM-CM5 (plains) and HadGEM2-ES (mountains) regional climate models. 


Multi-Scale SPI Calculation: Automated calculation of Standardized Precipitation Indices (SPI-3 and SPI-9) using Gamma probability distributions to identify agricultural and hydrological drought. 


Trend Analysis: Implementation of pixel-wise Mann-Kendall tests and Sen’s slope estimator to detect climate change signals across the 21st century. 

Technical Stack

Languages: Python (NumPy, SciPy, Pandas) 


Platforms: Google Earth Engine (GEE), ArcGIS (IDW Interpolation) 


Data Sources: MED-CORDEX (RCMs), PERSIANN-CCS-CDR, ERA5 Reanalysis 

Citation
If you use this methodology, please cite: 

Najmi, A., et al. (2023). Evaluation of PERSIANN-CCS-CDR, ERA5, and SM2RAIN-ASCAT rainfall products... Journal of Water and Climate Change.

Najmi, A., et al. (2026). Evaluation of Precipitation-Based Drought Indices Under Future Climate Change Scenarios... the Journal of Earth Systems and Environment (ESEV).
