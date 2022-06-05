# Mapping_Earthquakes
Creating an interactive dashboard to help visualize the earthquake data using JavaScript, Leaflt, Mapbox, and HTML.

## Overview
The goal of this project was to support the development of websites and mobile applications by using the latest GeoJSON data on earthquakes all over the world to create an interactive map. In the project, JavaScript, D3 and Leaflet were used to traversed these GeoJSON data files, and the resulting data was plotted on a mapbox map in response to an API request.

## Resources
- Datasets
  - Earthquakes [GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
  - Tectonic Plates [GeoJSON file](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
  - Major Earthquakes [GeoJSON file](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)

- Software
  - JavaScript
  - D3, Leaflet and Mapbox
  - GeoJSON files
  - HTML
  - Visual Studio Code


## Results

The final result of the project was a map of all the earthquakes across the world, with the size and color of the circles correlated with their magnitude.

Furthermore, the control legend offered the user three options for map styles (dark,satellite, or streets) and toggle options (on and off) between all earthquakes, major earthquakes and the tectonic plates.

- The map is showing tectonic plates and only major earthquakes (4.5 magnitude and higher):

- Dark view is showing all earthquakes: