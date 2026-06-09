# Limarí Valley Drought Analysis — NDVI Temporal Study (2016–2024)

Temporal analysis of vegetation changes in the Limarí Valley, Coquimbo Region, Chile, using Sentinel-2 satellite imagery and Google Earth Engine. This project monitors the impact of the Chilean megadrought and the partial vegetation recovery observed in 2024.

## Study Area
Limarí Province, Coquimbo Region, Chile. A semi-arid valley highly dependent on irrigation agriculture, severely affected by the megadrought that has impacted central Chile since 2010.

## Objectives
- Analyze vegetation changes over time using NDVI (2016, 2019, 2022, 2024)
- Quantify vegetation loss during the megadrought peak (2016–2022)
- Detect partial vegetation recovery between 2022 and 2024

## Methods
- Sentinel-2 SR Harmonized imagery filtered by cloud cover (<20%)
- NDVI calculation: (B8 - B4) / (B8 + B4)
- Two difference maps: drought impact (2022–2016) and recovery (2024–2022)
- Interactive map visualization with geemap

## Tools & Data
- Google Earth Engine (Python API)
- geemap, earthengine-api
- Sentinel-2 Level-2A (ESA) via GEE
- FAO GAUL administrative boundaries

## Key Findings
- Progressive vegetation decline from 2016 to 2022, consistent with the Chilean megadrought
- Partial vegetation recovery observed in 2024, likely associated with above-average precipitation in 2023–2024
- Agricultural areas in the valley floor show the most severe NDVI reductions

## Interactive Map
Open `ndvi_limari_map.html` in a browser to explore all NDVI layers interactively.

## Author
Constanza Morales | Geological Civil Engineer | 2026  
[GitHub](https://github.com/conimoralesg)
