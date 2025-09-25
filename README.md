# MATH261A-project
Project repository for MATH 261A project 1. 

## Title: Linking Education, Unemployment, and Poverty - Insights from California's CalEnviroScreen Data

## Overview
This project fits a simple linear regression of census-tract poverty on low educational attainment using CalEnviroScreen/ACS data, plus a supplemental model including unemployment.

## Repository structure


## Data 
Data used in this project is obtained from [CalEnviroScreen Data Hub](https://calenviroscreen-oehha.hub.arcgis.com/#Data). This data is released into the public domain by the California Office of Environmental Health Hazard Assessment (OEHHA). CalEnviroScreen 4.0 documentation and metadata from OEHHA. As public domain data, it has no copyright restrictions and can be used freely for any purpose, including commercial use.

OEHHA obtained the data used in the project from the American Community Survey (ACS) 2015–2019 5-year estimates from https://data.census.gov/. This data is also public domain data.

## How to reproduce
Place CalEnviroScreen_4.0_raw_data.csv (found [here](https://calenviroscreen-oehha.hub.arcgis.com/#Data)) in data/.
Open report.qmd and render to PDF: Quarto then Render. Requires R (≥ 4.0), Quarto, and the packages loaded in the setup chunk.

## External Resources
The final report and code were written by Isis Terrall Martinez, but the following resources were used for preliminary research:

* ChatGPT Edu (LLM-based chatbot): used for initial research about CalEnviroScreen Data Hub, R syntax, github repository troubleshooting, and troubleshooting problem with qq-plot that was very skewed when using ggplot2 (switched to qqnorm(resid(lm_fit) to resolve issue per Dr. Gao's suggestion)
* Peers in Math 261A (including Susan P. and Ali J.) to discuss project topics and peer review (pending)
* References noted in bibliography (including R software)
* Google for looking up synonyms for writing and looking into project topic possibilities

# Acknowledgments
This project repository is based on the template provided by [Rohan Alexander](https://github.com/RohanAlexander/starter_folder/tree/main).
