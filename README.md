# GEOG5990_Assignment

## Background

The **Index of Multiple Deprivation (IMD)** provides a comprehensive measure of deprivation across different regions in the UK. While the specific methodologies vary slightly between countries, IMD generally accounts for factors such as **income, employment, education, health, crime, housing access, and environmental quality**.

This project focuses on **London**, exploring the relationship between **IMD and education levels** to better understand how deprivation may impact educational attainment across the city.

## Data Sources

The analysis is based on the following datasets:

**English_imd_2019_london.csv** – Source: CDRC

Provides IMD scores and deciles for different areas in London.

IMD is calculated based on multiple weighted domains, including income deprivation (22.5%), employment (22.5%), education, skills, and training (13.5%), health (13.5%), crime (9.3%), housing & services (9.3%), and living environment (9.3%).

The data is available at the Lower Layer Super Output Area (LSOA) level, allowing for detailed spatial analysis.

**qualifications_London.csv** – Source: Census 2011

Contains data on educational attainment across London.

Includes categories such as *no qualifications, Level 1 (GCSE grades D-G), Level 2 (GCSE grades A-C), Apprenticeships, Level 3 (A-levels), and Level 4+ (Higher Education: Bachelor's, Master's, PhD)*.

Also aggregated at the LSOA level, making it compatible with IMD data for correlation analysis.

**LSOA_2011_London_gen_MHW.shp** – Source: Greater London Authority

A shapefile providing the geographical boundaries of London’s LSOAs.

Enables spatial visualization of deprivation and education levels using GIS tools.

## Project Structure

📂 GEOG5990_Assignment

│-- 📂 data              

│   ├── 📂 shapefile  

│   ├── English_imd_2019_london.csv

│   ├── qulifications_London.csv

│-- 201781475.ipynb

│-- README.md           



## Aims & Objectives

Visualize the spatial distribution of IMD deciles across London.

Analyze the correlation between IMD and education levels to identify potential patterns or disparities.

Assess whether lower education levels are associated with higher deprivation scores.

## Methodology

Data preprocessing and cleaning using Python (Pandas, Geopandas) or R.

Statistical correlation analysis (e.g., Pearson or Spearman correlation) to quantify the relationship between IMD and education levels.

