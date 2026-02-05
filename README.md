# Flood Vulnerability Assessment: Lekki-Epe Corridor 🌊

### 🗺️ [View the Interactive Map Here](https://terra-young.github.io/lekki_epe_flood/#11/6.5043/3.6952)

## Project Overview
As Lagos expands eastward, the Lekki-Epe corridor faces significant hydrological challenges. This project utilizes **Geospatial Intelligence** and **Multi-Criteria Decision Analysis (MCDA)** to model flood susceptibility, identifying safe zones for real estate development.

![Map Screenshot]([Link to a screenshot of your map])

## 📊 Key Findings
- **Total Area Analyzed:** ~1,437 sq km.
- **High Risk:** **35%** of the corridor is classified as critical wetland/flood zones.
- **Moderate Risk:** **37%** requires engineering intervention (drainage/filling).
- **Safe Zone:** Only **28%** is naturally suitable for immediate development.

## 🧠 Methodology (AHP-MCDA)
The susceptibility index was calculated using a weighted overlay of four hydro-geomorphic factors:
1.  **Topographic Wetness Index (35%):** Flow accumulation potential.
2.  **Distance to Water (30%):** Proximity to Lagoon/Ocean.
3.  **Slope (20%):** Surface runoff velocity.
4.  **NDVI (15%):** Land cover permeability.

## 🛠️ Tech Stack
- **Analysis:** QGIS 3.x (SAGA Hydrology, GRASS)
- **Data:** Sentinel-2 (ESA), Copernicus GLO-30 DEM, OpenStreetMap.
- **Visualization:** Leaflet.js (via qgis2web).
- **Hosting:** GitHub Pages.

---
*Created by [Eniola Akinnibi] - Risk Analyst & GIS Specialist*
