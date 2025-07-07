# 📊 Crime Rate Analysis in Washington, D.C.

This repository contains an R project that analyzes crime rate trends in Washington, D.C. over the past five years.  
The project leverages various data visualization techniques to explore patterns in property crimes and their relation to alcohol-licensed business locations.

👉 **[View the full interactive report on Rpubs](https://rpubs.com/Manta/1322691)**

---

## 💡 Project Overview

### ✅ Objective
- To explore the temporal and spatial patterns of property crimes in Washington, D.C.
- To investigate the potential correlation between crime occurrences and the distribution of alcohol-licensed businesses.

### ✅ Data Sources
- **Property crime data** (last 5 years) from the Metropolitan Police Department:  
  [https://crimecards.dc.gov/all:property%20crimes/all:weapons/5:years/citywide:point](https://crimecards.dc.gov/all:property%20crimes/all:weapons/5:years/citywide:point)
- **Alcohol license business locations** from Open Data DC:  
  [https://opendata.dc.gov](https://opendata.dc.gov)

---

## 🔍 Methods & Visualizations

- **Temporal Analysis:**  
  Trends over time using line graphs and smoothed curves (e.g., LOESS).  
- **Spatial Analysis:**  
  - Choropleth and cartogram maps representing crime density by district.
  - Overlay of crime hotspots with alcohol-licensed business locations using `leaflet` interactive maps.
- **Correlation Analysis:**  
  Analysis of proximity patterns between crime locations and alcohol-serving businesses.

---

## ✨ Key Features

- Built with R (`ggplot2`, `leaflet`, `cartogram`, `sf`, `dplyr`, and more).
- Interactive mapping with `leaflet` for detailed spatial exploration.
- Uses official city data sources ensuring reliability of analysis.
- Combines time series trends with geospatial insights.

---

## ⚡ Notes

- The code and data processing steps are available in this repository.
- The report is published on Rpubs and can be accessed via the link at the top.

---

## 📎 Citation

> Lee, W. & Seo, J. (2025). *Crime Rate in D.C.* R project for CDS301.
