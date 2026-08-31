# 🗺️ Landfill Locations in India

## 📌 Project Overview

This project maps identified landfill locations across India using geographic coordinates.

The aim is to visualize the spatial distribution of landfill sites and provide the dataset in a format that can be explored and reused in GIS software.

## 🌐 Interactive GIS Data

The landfill locations are available as a GeoJSON dataset.

👉 **[View Interactive Map](./disposal_map.geojson)**

The GeoJSON file can also be downloaded and opened in QGIS, ArcGIS, or other GIS software.

## 🖼️ Final Map

![Landfill Locations in India](./disposal_map.png)

## 🛠️ Software Used

- QGIS
- GIS data processing
- GeoJSON
- Cartographic layout design

## 📊 Dataset

The dataset contains:

| Field | Description |
|---|---|
| City | City where the landfill is located |
| State | State where the landfill is located |
| Landfill Name | Name of the landfill |
| Latitude | Geographic latitude |
| Longitude | Geographic longitude |
| Type | Type of landfill |
| Status | Current status |

## 🔎 GIS Methods

- Imported CSV data into QGIS
- Used latitude and longitude to create point features
- Assigned WGS 84 / EPSG:4326
- Visualized landfill locations across India
- Prepared a cartographic map layout
- Exported the GIS data as GeoJSON
- Created a final map for presentation

## 📥 Files

- **[disposal_map.geojson](./disposal_map.geojson)** — Interactive and downloadable GIS data
- **[disposal_map.png](./disposal_map.png)** — Final map
- **[DISPOSAL_IN_INDIA.qgz](./DISPOSAL_IN_INDIA.qgz)** — QGIS project file

## 📍 Project Status

Completed GIS mapping project.
