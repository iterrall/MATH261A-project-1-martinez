# MATH261A-project
Project repository for MATH 261A project 1 by Isis Martinez, SJSU

## Title: Linking Education, Unemployment, and Poverty - Insights from California's CalEnviroScreen Data

## Overview
This project fits a simple linear regression of census-tract poverty on low educational attainment using CalEnviroScreen 4.0 and the American Community Survey (ACS) data, plus a supplemental model including unemployment.

## Repository structure
MATH261A-project/  
│  

├── paper/

|   └── math261a_martinez_paper.pdf       # Rendered final report

|   └── math261a_martinez_paper.qmd       # Quarto report for analysis including R code

|   └── references.bib                    # References for the project report

│   └── CalEnviroScreen_4.0_raw_data.csv  # Raw dataset allowed by open source data license

│

├── README.md                              # Project description, sources, and reproducible workflow

## Data and License Information 
Data used in this project is obtained from [CalEnviroScreen Data Hub](https://calenviroscreen-oehha.hub.arcgis.com/#Data). This data is released into the public domain by the California Office of Environmental Health Hazard Assessment (OEHHA). CalEnviroScreen 4.0 documentation and metadata from OEHHA. 

OEHHA obtained the data used in the project from the American Community Survey (ACS) 2015–2019 5-year estimates from https://data.census.gov/. This data is also public domain data with an open license from the U.S. Government.

As public domain data, both datasets have no copyright restrictions and can be used freely for any purpose, including commercial use.

## How to reproduce
Download CalEnviroScreen_4.0_raw_data.csv found [here](https://calenviroscreen-oehha.hub.arcgis.com/#Data) in data/.
Open report.qmd and render to PDF: Quarto then Render. Requires R (≥ 4.0), open math261a_martinez_paper.qmd in RStudio and render it to PDF. From there, ensure you have the packages listed in the first R chunk and then click Quarto → Render.

## External Resources
The final report and code were written by Isis Terrall Martinez, but the following resources were used for preliminary research:

* ChatGPT Edu (LLM-based chatbot): used for initial research about CalEnviroScreen Data Hub, R syntax, github repository troubleshooting, and troubleshooting problem with qq-plot that was very skewed when using ggplot2 (switched to qqnorm(resid(lm_fit) to resolve issue per Dr. Gao's suggestion)
* Peers in Math 261A (including Susan P. and Ali J.) to discuss project topics and peer review by Siling G.
* References noted in bibliography (including R software)
* Google for looking up synonyms for writing and looking into project topic possibilities

# Acknowledgments
This project repository is based on the template provided by [Rohan Alexander](https://github.com/RohanAlexander/starter_folder/tree/main).
