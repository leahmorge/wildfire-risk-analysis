# Wildfire Risk Analysis in the United States (1992–2020)

## Overview
This project analyzes historical wildfire patterns across the United States from 1992–2020 to explore factors that contribute to wildfire risk. Using wildfire occurrence data and population statistics, the analysis examines trends in fire frequency, ignition causes, fire size distribution, and the spatial relationship between wildfire activity and population density in highly fire-prone states.

The goal of this project is to demonstrate how exploratory data analysis can help identify patterns relevant to wildfire exposure and risk assessment.

## Objectives
- Examine long-term trends in wildfire occurrence in the United States
- Identify the most common causes of wildfire ignition
- Analyze the distribution of wildfire sizes
- Explore relationships between wildfire activity and population density in high-risk states

## Tools & Technologies
- Python (Pandas, GeoPandas, Matplotlib, Seaborn)
- Jupyter Notebook
- ArcGIS (shapefiles used for mapping and spatial analysis)

## Data Sources
Wildfire data was obtained from the US Forest Service Fire Program Analysis Fire-Occurrence Database (FPA-FOD), which contains records of wildfire incidents across the United States (1992-2020).

Shapefiles of states and counties (including population data) were obtained from Natural Earth Data and ArcGIS Online.

## Methods
The analysis was conducted in Python using a Jupyter Notebook.
Key steps included:
1. Cleaning and preparing wildfire occurrence data
2. Aggregating wildfire counts by year to identify long-term trends
3. Analyzing wildfire ignition causes
4. Examining the distribution of wildfire sizes
5. Mapping wildfire locations and comparing them with county-level population density in the most wildfire-affected states
Visualizations were created to highlight patterns in wildfire frequency, causes, and spatial distribution\

## Key Findings

- **Wildfire frequency is consistently high:** Annual wildfire counts in the U.S. generally range from 60,000–100,000 fires, with occasional spikes (e.g., ~120,000 in 2006). Wildfires are a persistent hazard rather than an occasional anomaly.  

- **Ignition causes vary and data gaps exist:** Many incidents have “Missing/Undetermined” causes. Lightning-ignited fires account for a disproportionate share of burned area, while human-caused fires occur more frequently but tend to be smaller.  

- **Spatial distribution is uneven:** California, Texas, and Georgia have the highest wildfire counts, reflecting differences in climate, vegetation, and land management practices.  

- **Wildfire exposure differs by state and population density:**  
  - California: High wildfire activity in regions near major population centers increases human exposure risk.  
  - Texas: Wildfires are concentrated outside major urban centers, highlighting wildland–urban interface dynamics.  
  - Georgia: Wildfires are broadly distributed with less correlation to urban populations, indicating ecological impacts may outweigh direct human risk in many areas.  

- **Implication for risk assessment:** Regional differences in wildfire occurrence and population proximity underscore the importance of tailored mitigation and preparedness strategies, including land-use policy, vegetation management, and emergency response planning.

## Repository Contents

- wildfire_analysis.ipynb – Jupyter Notebook containing the full analysis
- data/ – Documentation of data sources used
- README.md – This project description

## Author
Leah Morgenstern - Environmental Science, GIS, and Data Analytics
