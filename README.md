# 📊 Crime Rate Analysis in Washington, D.C.

This repository contains an R project analyzing property crime patterns in Washington, D.C.  
The project combines time series analysis and geospatial visualization to explore the relationships between crime, environmental factors, and social infrastructure.

👉 **[View the full interactive report on Rpubs](https://rpubs.com/Manta/1322691)**

---

## 💡 Project Overview

### ✅ Objectives
- Analyze temporal and spatial patterns of property crimes in D.C. over the past five years.
- Investigate how crime relates to external factors such as:
  - Temperature (seasonality)
  - Alcohol-licensed businesses (nightlife clusters)
  - Homeless service facilities (urban inequality)
  - Time of day

---

## 📂 Data Sources
- **Property crimes (5 years)**: Metropolitan Police Department  
  [https://crimecards.dc.gov](https://crimecards.dc.gov)
- **Alcohol license business locations**: Open Data DC  
  [https://opendata.dc.gov](https://opendata.dc.gov)
- **Homeless service facilities**: Open Data DC  
  [https://opendata.dc.gov](https://opendata.dc.gov)
- **Temperature data**: VisualCrossing  
  [https://www.visualcrossing.com](https://www.visualcrossing.com)

---

## 🔍 Methods & Visualizations

### 📈 Temporal Analysis
- Crime trends over time: Yearly and monthly summaries of property crimes by type.
- Dual-axis time series plots showing theft counts and average monthly temperature.
- Theft distribution by time of day: Polar bar charts highlight peak theft hours (3pm-6pm).

### 🗺 Spatial Analysis
- Choropleth and cartogram maps visualizing crime density across districts.
- Interactive buffer analysis (500m radius) around:
  - Homeless facilities: Highest theft count near Legal Assistance Project (5,364 incidents).
  - Alcohol businesses: Highest theft count near Mama nightclub (5,713 incidents).
- Leaflet maps highlight spatial clustering of theft near nightlife and homeless facilities.

### 📊 Correlation Analysis
- Correlation matrix and heatmaps showing relationships between thefts, alcohol businesses, and homeless service locations at the tract level.

---

## ✨ Key Insights
- Theft incidents peak during afternoon hours (3pm–6pm).
- Higher theft counts cluster around D.C.’s U Street NW (“Black Broadway”) nightlife area and near certain homeless facilities.
- Strong correlation between theft rates and environmental/social factors: temperature, nightlife density, homelessness.

---

## ⚡ Notes
- The project demonstrates a combination of quantitative analysis and geospatial visualization to identify high-risk zones.
- Limitations include overlapping buffers and the complexity of underlying social dynamics.
- All code, data processing, and visualizations are included in this repository.

---

## 👀 Recommendation

If you're planning to visit D.C., especially the U Street NW area — also known as Black Broadway — keep an eye on your belongings in the afternoon!
