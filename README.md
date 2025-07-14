# berlin-urban-mobility-analysis
# 🚦 Berlin Urban Mobility Analysis

This project analyzes urban traffic movement across Berlin using open-source traffic sensor data collected over 6 months (Jan–June 2025). The goal is to explore pedestrian, bike, and car movement patterns using Python and geospatial tools.

---

## 📌 Objectives

- Load and clean 6 months of Berlin traffic data
- Merge with spatial segment geometry (GeoJSON)
- Calculate average traffic by segment (bikes, pedestrians, cars)
- Visualize in an interactive street-level map using `folium`

---

## 🧰 Tools & Technologies

- **Python**: pandas, geopandas, folium
- **Mapping**: GeoJSON, OpenStreetMap tiles
- **Visualization**: Folium interactive maps
- **Other**: Jupyter Notebook, Tableau (optional)

---

## 🗺️ Outputs

- 📍 `berlin_bike_traffic_map.html`: Interactive street-level map
- 📁 `berlin_mobility_summary.geojson`: Spatial data for mapping
- 📊 `berlin_mobility_tableau.csv`: Aggregated data for Tableau/analysis

---

## 📸 Preview

![Preview of Berlin Bike Traffic Map](screenshots/preview.png)

---

## 💡 Key Learnings

- Spatial joins with Python
- Working with real-world traffic sensor data
- Urban mobility and geospatial storytelling
- Exporting for GIS and dashboard tools

---

## 🧪 How to Run

1. Clone this repo  
2. Install dependencies  
