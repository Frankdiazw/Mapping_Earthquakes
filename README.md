# Mapping Earthquakes

## Overview of the project
For this module the challenge was to create an interactive data visualizations with interactive features on earthquakes around the world. The objective was to promote a new and simple way to visualize data through desktop and mobile phones for the Disaster Reporting Network. The GeoJSON data from the U.S. Geological Survey Website was used to develop the desktop and mobile aplication, uing Javascript, the D3 and leaflet libraries to plot the data on a Mapbox map through an API request. 

- ### Tectonic Plate Data
Using the knowledge adquired of JavaScript, Leaflet.js, and geoJSON data, the tectonic plate data was added using d3.json(), that data was added using the geoJSON() layer, then the tectonic plate LineString data was set to stand out on the map, and finally the tectonic plate data was added to the overlay object with the earthquake data. The result can be seen in the following figure:

![](https://github.com/Frankdiazw/Mapping_Earthquakes/blob/main/static/images/Deliverable%201.png)
- Figure 1. Map with the tectonic plate data.

- ### Major Earthquake Data
Using the knowledge adquired of JavaScript, Leaflet.js, and geoJSON data, the major earthquake data was added to the map using d3.json(). Then color was added and the radius of the circle markers were set based on the magnitude of earthquake, and a popup marker was added for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON(). The result can be observed in the following figure:

![](https://github.com/Frankdiazw/Mapping_Earthquakes/blob/main/static/images/Deliverable%201.png)

