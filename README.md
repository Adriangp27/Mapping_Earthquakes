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
![streetversion](https://user-images.githubusercontent.com/99752443/172067841-bef7d0c6-edfb-44a0-96ff-f7da3d2f8066.png)

The final result of the project was a map of all the earthquakes across the world, with the size and color of the circles correlated with their magnitude.

![legend1](https://user-images.githubusercontent.com/99752443/172067855-ac3be181-13e4-46bc-8cf6-3e2b519b9b76.png)

![legend2](https://user-images.githubusercontent.com/99752443/172067874-26be823c-bba6-42a5-9881-6e98a4722e77.png)

Furthermore, the control legend offered the user three options for map styles (dark,satellite, or streets) and toggle options (on and off) between all earthquakes, major earthquakes and the tectonic plates.

- The map is showing tectonic plates and only major earthquakes (4.5 magnitude and higher):

![earthquakeswithmagnitude](https://user-images.githubusercontent.com/99752443/172067893-f3453fec-b50b-4c1f-9fd6-2318db2b2eeb.png)


- Dark view is showing all earthquakes:

![darkversionwithallearhquakes](https://user-images.githubusercontent.com/99752443/172067907-1a6e451e-34b2-47fe-a663-5eb6d65c4d0f.png)
