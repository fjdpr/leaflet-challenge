# Earthquake Visualization Dashboard

## Summary
This project involves the analysis and visualization of earthquake data using Leaflet and D3.js libraries. The goal is to create an interactive map showing earthquake occurrences and tectonic plates boundaries.

## Objectives
- Use Leaflet to create interactive maps.
- Use D3.js to load and process GeoJSON data.
- Visualize earthquake data on the map.
- Add layers for tectonic plates.
- Include interactive features such as popups and a legend.

## Data Description
The dataset includes:
- **USGS Earthquake Data**: GeoJSON data for earthquakes from the [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson).
- **Tectonic Plates Data**: GeoJSON data for tectonic plates boundaries from the [PB2002 Boundaries dataset](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json).

## Included Scripts
1. **index.html**:
   - Structures the webpage and defines the map container.
   - Includes references to Leaflet and D3.js libraries.

2. **logic.js**:
   - Creates the map and adds base layers.
   - Loads earthquake and tectonic plates data using D3.js.
   - Adds interactive features such as circle markers, popups, and a legend.

3. **style.css**:
   - Provides styling for the map and legend.

## Requirements
- Leaflet.js
- D3.js

## Instructions

### Getting Started
1. Ensure you have an internet connection to load the Leaflet.js and D3.js libraries.
2. Open `index.html` in your browser.

### Features
- **Map Layers**: Toggle between different map layers (Street and Satellite).
- **Earthquake Data**: Visualize earthquakes with circle markers sized by magnitude and colored by depth.
- **Tectonic Plates**: Overlay tectonic plates boundaries on the map.
- **Legend**: Displays a legend indicating the depth of earthquakes.

## Deployment
The application is deployed on GitHub Pages. You can access it [here](https://fjdpr.github.io/leaflet-challenge/).

## References
- USGS Earthquake Hazards Program. (n.d.). Retrieved from [USGS](https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php)
- PB2002 Boundaries dataset. (n.d.). Retrieved from [GitHub](https://github.com/fraxen/tectonicplates)

## Contributions
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
