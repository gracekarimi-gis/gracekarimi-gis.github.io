# Hi, I'm Grace Karimi 👋

### Geomatics Engineer & GIS Developer | Nairobi, Kenya

I build geospatial solutions, from interactive web maps and remote sensing pipelines to spatial databases and drone data processing. My work focuses on applying GIS and earth observation technologies to real-world challenges across Kenya and East Africa.

---

### 🛠️ Tech Stack

**GIS & Remote Sensing**
`ArcGIS Pro` `ArcGIS Online / StoryMaps` `QGIS` `JOSM` `Google Earth Engine` `OpenDroneMap`

**Programming**
`Python` `GeoPandas` `Shapely` `Rasterio` `R` `SQL`

**Web GIS**
`Leaflet.js` `Mapbox GL JS` `GeoServer` `PostGIS`

**Surveying & Data Collection**
`Total Stations` `GPS Receivers` `UAV / Drone Surveys` `AutoCAD`

---

### 📌 Featured Projects

| Project | Description | Tools |
|--------|-------------|-------|
| 🗺️ [Nairobi Road Network Analysis](#) | Accessibility and connectivity analysis of Nairobi's road network | Python, OSMnx, GeoPandas |
| 🐦 [Hexagons for Hornbills](https://arcg.is/00D0vv0) | Congo Basin hornbill conservation StoryMap — H3 hexagonal density binning and Getis-Ord Gi* hotspot analysis against the DRC's 30x30 protected-area targets | ArcGIS Online, StoryMaps, H3, Getis-Ord Gi* |
| 🌾 [Tharaka-Nithi Aridity & Food Security](https://arcg.is/14i0eK1) | 20-year (2003–2023) aridity trend analysis linking NDVI/CHIRPS rainfall data to a 39% decline in sorghum production, with hotspot wards and a KALRO drought-resistant variety recommendation | QGIS, NDVI, CHIRPS, ArcGIS StoryMaps |
| 🌍 [Land Use Change Detection — Kenya](#) | Multi-year LULC change analysis using Sentinel-2 imagery | Google Earth Engine, Python |
| 💧 [Flood Risk Dashboard](#) | Interactive flood susceptibility map for a Kenyan watershed | DEM, QGIS, Leaflet.js |
| 🚁 [Drone Processing Pipeline](#) | Automated orthophoto and DSM generation from UAV imagery | OpenDroneMap, QGIS |
| 🌐 [GIS REST API](#) | Spatial data API serving GeoJSON endpoints | FastAPI, PostGIS, Python |

*(Links marked `#` will be updated as projects are published)*

---

### 💼 Experience

- **Geomatics Intern** - Kenya Rural Roads Authority (KeRRA), Sep–Dec 2025
- **Geospatial Analyst Intern** - Geodev Kenya Limited, Jan–May 2024
- **Geomatics Research Assistant** - Dedan Kimathi University of Technology, Jan–March 2023

### 📚 Training & Externships

- **RCMRD** - *Transforming Maps into Stories and Data into Decisions*, 2026-completed the GeoHex Conservation Challenge, submitting the "Hexagons for Hornbills" StoryMap
- **UN Mappers Kenya Youth Climate Mapping Externship**, June–August 2026-humanitarian OSM mapping with JOSM (Ruai Ward flood-resilience mapathon, HOT Tasking Manager) and a climate-impact analysis project on aridity and food security in Tharaka-Nithi County

---

### 🎓 Education

**BSc Geomatics Engineering & GIS** - Dedan Kimathi University of Technology (2021–2025)

---

### 📫 Let's Connect

- 📧 gracekarimi610@gmail.com
- 🌐 [Portfolio Website](https://gracekarimi-gis.github.io) *(coming soon)*
- 💼 [LinkedIn](#) *(add your link)*

---

*Open to GIS Developer, Geospatial Analyst, and Remote Sensing roles across Kenya and East Africa.*

---

## 📁 Projects

### 🗺️ [Nairobi Road Network Analysis](https://github.com/gracekarimi-gis/nairobi-road-network)
A comprehensive geospatial analysis of Nairobi's entire road network using Python and open-source GIS tools.

**Key Findings:**
- 🛣️ 89,057 road segments spanning 9,495 km total
- 📍 36,558 intersections across the city
- 🏘️ 83% of roads are residential — reflecting dense urban neighbourhoods
- ⚠️ Only 0.6% are primary roads — a key factor in Nairobi's congestion

**Tools:** `Python` `OSMnx` `GeoPandas` `Folium` `Matplotlib`

---

### 🐦 [Hexagons for Hornbills](https://arcg.is/00D0vv0)
A StoryMap built for RCMRD's GeoHex Conservation Challenge, using H3 hexagonal binning to analyze hornbill density in the Congo Basin against the DRC's progress toward 30x30 protected-area targets.

**Key Findings:**
- 🗺️ 950 DRC hornbill telemetry points binned into 52 H3 resolution-4 hexagons
- 📊 Getis-Ord Gi* hotspot analysis run on the hex density grid
- 🌍 DRC terrestrial protection at 14.9% (needs 15.1 more points to hit 30%); marine protection at 0.5%
- 🏛️ Governance data gap: 89.2% of protected areas have no reported governance type

**Tools:** `ArcGIS Online` `StoryMaps` `H3` `Getis-Ord Gi*`

---

### 🌾 [Tharaka-Nithi Aridity & Food Security](https://arcg.is/14i0eK1)
A 20-year aridity trend analysis (2003–2023) built during the UN Mappers Kenya Youth Climate Mapping Externship, combining NDVI and CHIRPS rainfall data to assess food security impact in Tharaka-Nithi County.

**Key Findings:**
- 📈 Aridity Index built from NDVI + CHIRPS rainfall, aggregated to ward level via zonal statistics
- 🔥 Six hotspot wards identified: Mukothima, Gatunga, Nkondi, Marimanti, Chogoria, Chiakagira
- 🌾 Sorghum production fell 39% (18,097 to 11,066 tons) between 2019–2023
- 💡 Recommends prioritizing KALRO's drought-tolerant sorghum varieties in hotspot wards

**Tools:** `QGIS` `NDVI` `CHIRPS` `ArcGIS StoryMaps`
