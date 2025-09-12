# NERC Digital Gathering Hackathon 2025

## Overview

This repository contains materials for the **NERC Digital Gathering Hackathon 2025**, designed to help participants understand and work with environmental data from the NERC CEDA (Centre for Environmental Data Analysis) data archive.

The hackathon challenges are presented through interactive Jupyter Notebooks that run on the **JASMIN HPC** (High Performance Computing) system operated by NERC. JASMIN provides powerful computational resources and direct access to the extensive CEDA data archive, enabling participants to work with large-scale environmental datasets efficiently.

## Hackathon ethos and intention

The hackathon is not a competitive exercise. Instead we are keen to help show you the wealth of data available in the extraordinary CEDA data archives of NERC and to run through some realistic 'exploratory data analysis' with some of the key datasets. Some of the notebooks require editing to run, and some may seem complete, but there is always more to add. Furthermore, in writing and running the code you will be using the notebook server running in JASMIN, NERC's HPC system - and that has direct access to the CEDA data files. A powerful combination. The hackathon will therefore also show you how to use JASMIN to run code.

Staff from JASMIN and CEDA will be on-hand to help you with access to the system and have prepared a series of training accounts for the day for all delegates. They advise that it is best to use these accounts for the event even if you already have your own JASMIN and CEDA accounts - really just to save time. But they will be able to help provide advice on next steps if you like what you see. We hope you enjoy the event!

## About NERC and CEDA

**NERC** (Natural Environment Research Council) is the UK's leading funder of independent research, training and innovation in environmental science, see https://www.ukri.org/councils/nerc/. The **CEDA Archive** is NERC's primary data centre for atmospheric and earth observation research, housing petabytes of environmental data including weather observations, climate models, satellite data, and more. See https://data.ceda.ac.uk

## Hackathon Focus

The hackathon encourages exploration of three key environmental datasets:

- **MIDAS** (Met Office Integrated Data Archive System): Raw weather observations from land and marine surface stations, in CSV format.
- **ECMWF** (European Centre for Medium-Range Weather Forecasts): Global weather forecasts and climate reanalyses, in NetCDF format.  
- **HadUK-Grid**: Gridded climate variables for the UK derived from interpolated land surface observations, in NetCDF format.
- **Soils and Land Cover**: Focus on soils and land cover data with challenges for working with spatial environmental datasets for Bedfordshire, in CSV format.

Participants can choose to focus their analysis on either the UK as a whole or specifically on Bedfordshire, where the hackathon is located.

We hope you will have time to run and review all four notebooks, but if not you can complete them later.

## Notebook Files

### 1. NERC_DG_Hackathon_ECMWF.ipynb

This notebook focuses on **ECMWF (European Centre for Medium-Range Weather Forecasts) data** and provides challenges for working with global weather and climate reanalysis data.

**Key Features:**
- Loading and processing NetCDF data from the CEDA archive
- Temperature unit conversion (Kelvin to Celsius)
- Global and regional data visualisation
- UK and Bedfordshire geographical focus
- Interactive data animation techniques
- Time-series analysis and statistical processing

**Challenges Include:**
- **Load and Process ECMWF Data**: Working with NetCDF data structure and metadata
- **Temperature Unit Conversion**: Converting from Kelvin to Celsius with proper attributes
- **Global Temperature Visualisation**: Creating informative temperature maps and plots
- **UK Regional Analysis**: Focusing on UK-wide patterns and time-series analysis
- **Bedfordshire Local Analysis**: Detailed local climate pattern examination
- **Data Animation and Visualisation**: Creating engaging animated temperature visualisations

### 2. NERC_DG_Hackathon_MIDAS.ipynb

This notebook focuses on **MIDAS (Met Office Integrated Data Archive System) data** and provides challenges for working with station-based weather observations.

**Key Features:**
- Processing CSV-format weather station data
- Time-series analysis and trend detection
- Statistical analysis of temperature patterns
- Data cleaning and preprocessing techniques
- Multiple challenge scenarios for different applications

**Challenges Include:**
- **Weather Storytelling Dashboard**: Creating engaging visualisations and narratives from weather data
- **Rainfall Prediction**: Using machine learning to predict rainfall from historical weather data
- **Flood Risk Index**: Combining rainfall, soil moisture, and other factors to assess flood risk
- **Renewable Energy Forecasting**: Estimating solar and wind energy potential from weather data
- **Data Cleaning Showdown**: Building robust data cleaning pipelines for messy environmental datasets

### 3. NERC_DG_hackathon_HadUK.ipynb

This notebook focuses on **HadUK-Grid data** and provides challenges for working with gridded UK climate data and river-basin aggregations.

**Key Features:**
- Working with NetCDF gridded climate data
- UK National Grid (OSGB) projection mapping
- River-basin aggregation analysis
- Comparative climate analysis across time periods
- Spatial data visualisation with cartopy

**Challenges Include:**
- **Open and Inspect HadUK-Grid Data**: Working with NetCDF data structure and metadata
- **UK Map Plotting**: Creating maps using OSGB projection with cartopy
- **River-Basin Exploration**: Working with aggregated basin-level climate data
- **Monthly Time Series Analysis**: Building time series for specific river basins
- **Climate Period Comparison**: Comparing rainfall patterns between 1961-1990 and 1991-2020

### 4. NERC_DG_Hackathon_SoilsAndLandCover.ipynb

This notebook focuses on **soils and land cover data** and provides challenges for working with spatial environmental datasets for Bedfordshire. The soil data comes from Cranfield University's LandIS Land Information System, see https://www.landis.org.uk.

**Key Features:**
- Loading and processing CSV datasets from external URLs
- Statistical analysis of land cover and soil properties
- Spatial analysis and grid comparison
- Intercomparison between different environmental datasets
- Data visualisation and pattern identification

**Challenges Include:**
- **Load and Explore Land Cover Data**: Working with CORINE Land Cover data structure and analysis
- **Load and Explore Soils Data**: Comprehensive analysis of NATMAP Soils dataset
- **Statistical Analysis and Visualisation**: Creating informative visualisations and identifying patterns
- **Spatial Analysis and Grid Comparison**: Understanding spatial relationships between datasets
- **Advanced Intercomparison Analysis**: Identifying correlations and relationships between land cover and soil properties

## Getting Started
Wait - How do i get a JASMIN account?
Don't worry, we will provide you a special pre-configured training account on the day of the hackathon with access to all the data! In the meanwhile you could also apply both for a JASMIN account here https://jasmin.ac.uk, and a CEDA account here https://archive.ceda.ac.uk.

1. **Access JASMIN**: The notebooks are designed to run on the JASMIN HPC system with direct access to CEDA data
2. **Choose Your Focus**: Select from the ECMWF, MIDAS, HadUK-Grid, or Soils & Land Cover notebook based on your interests
3. **Follow the Challenges**: Each notebook contains 5-6 structured challenges with background context, clear tasks, and success criteria
4. **Explore the Data**: Use the provided geographical coordinates to focus on UK-wide or Bedfordshire-specific analysis

## Useful Resources

- [CEDA Data Archive](https://data.ceda.ac.uk)
- [CEDA Help Documentation](https://help.ceda.ac.uk)
- [MIDAS User Guide](https://zenodo.org/records/7357335)
- [ECMWF Website](https://www.ecmwf.int)
- [JASMIN Notebooks Service Help](https://help.jasmin.ac.uk/docs/interactive-computing/jasmin-notebooks-service/)

## Geographical Coordinates

- **UK Bounding Box**: -10°W to 3°E, 49°N to 61°N
- **Bedfordshire Bounding Box**: -0.89°W to 0.23°E, 51.95°N to 52.49°N

---

*This hackathon provides an excellent opportunity to explore real environmental data and develop skills in data analysis, visualisation, and environmental science applications.*
