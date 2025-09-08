# NERC Digital Gathering Hackathon 2025

## Overview

This repository contains materials for the **NERC Digital Gathering Hackathon 2025**, designed to help participants understand and work with environmental data from the NERC CEDA (Centre for Environmental Data Analysis) data archive.

The hackathon challenges are presented through interactive Jupyter Notebooks that run on the **JASMIN HPC** (High Performance Computing) system operated by NERC. JASMIN provides powerful computational resources and direct access to the extensive CEDA data archive, enabling participants to work with large-scale environmental datasets efficiently.

## About NERC and CEDA

**NERC** (Natural Environment Research Council) is the UK's leading funder of independent research, training and innovation in environmental science. The **CEDA Archive** is NERC's primary data centre for atmospheric and earth observation research, housing petabytes of environmental data including weather observations, climate models, satellite data, and more.

## Hackathon Focus

The hackathon encourages exploration of three key environmental datasets:

- **MIDAS** (Met Office Integrated Data Archive System): Raw weather observations from land and marine surface stations in CSV format
- **ECMWF** (European Centre for Medium-Range Weather Forecasts): Global weather forecasts and climate reanalyses in NetCDF format  
- **HadUK-Grid**: Gridded climate variables for the UK derived from interpolated land surface observations in NetCDF format

Participants can choose to focus their analysis on either the UK as a whole or specifically on Bedfordshire, where the hackathon is located.

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
- Loading ECMWF data in NetCDF format
- Converting temperature units from Fahrenheit to Celsius
- Plotting global temperature data
- Focusing analysis on UK and Bedfordshire regions
- Creating animated visualisations of temperature data

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

## Getting Started

1. **Access JASMIN**: The notebooks are designed to run on the JASMIN HPC system with direct access to CEDA data
2. **Choose Your Focus**: Select either the ECMWF or MIDAS notebook based on your interests
3. **Follow the Challenges**: Each notebook contains structured challenges with starter code and success criteria
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
