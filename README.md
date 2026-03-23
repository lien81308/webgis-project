# Taipei Crime Mapper: Interactive WebGIS Platform

An interactive WebGIS application for analyzing and visualizing crime data in Taipei City. This project was developed as the final report for the **"Web Geographic Information System"** course (113-1).

## Live Demo
[View the Live Map](https://lien81308.github.io/webgis-project/)

## Key Features
- **Spatial Visualization**: Interactive heatmaps and point clusters for residential burglary, car theft, and scooter theft.
- **Buffer Analysis**: Real-time proximity calculation using **Turf.js** to analyze crime occurrences within custom radiuses.
- **Data Filtering**: Filter crime data by type and time period.
- **Statistical Dashboard**: Integrated charts for temporal analysis (built with Chart.js).
- **Responsive UI**: Interactive sidebars and map controls.

## Tech Stack
- **WebGIS Engine**: Mapbox GL JS
- **Spatial Analysis**: Turf.js
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Data Format**: GeoJSON
- **Hosting**: GitHub Pages

## Data Source
The crime data used in this project is sourced from the **[Taipei City Open Data Platform (臺北市資料大平台)](https://data.taipei/)**, specifically:
- **Residential Burglary** (住宅竊盜點位資訊)
- **Car Theft** (汽車竊盜點位資訊)
- **Motorcycle Theft** (機車竊盜點位資訊)
- **Bicycle Theft** (自行車竊盜點位資訊)

## Credits & Team
This project was a collaborative effort by **Group 2**:
- **邱辰安**: Project Lead, Lead Developer (Heatmap & Geocoding).
- **連彥博 (Me)**: Developer (Buffer Analysis & UI/UX Design).
- **鄭哲愷**: Developer (Statistical Dashboard & Theme Toggle).

## Acknowledgments
- **Instructor**: Prof. Kuo, Chiao-Ling
- **Institution**: National Taiwan University, Department of Geography
