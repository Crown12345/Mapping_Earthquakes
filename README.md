# Mapping_Earthquakes

## Overview 
Using Leaflet.js API, a map was populated with GeoJSON earthquake data from a URL.  Each earthquake with a magnitude greater than 4.5 is visually represented with a circle and color, and a larger magnitude will have a larger diameter circle.  Additionally, each earthquake marker has a popup marker that displays the magnitude of the earthquake and the location.  Users can choose to view the map in street view, satellite street view, or light view.  Users can also select from the following layers: Earthquakes, Tectonic Plates, or Major Earthquakes.

## Dependencies
- JavaScript
    - D3.js
    - Leaflet.js
- Mapbox
- GeoJSON data
    - [USGS All Earthquakes in the Last 7 Days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
    - [USGS Earthquake with > 4.5 Magnitude in the Last 7 Days](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)



## Results

### Deliverable 1:
Using JavaScript, Leaflet.js, and geoJSON data, add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.


### Deliverable 2:
Using JavaScript, Leaflet.js, and geoJSON data, add major earthquake data to the map using d3.json(), and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().



### Deliverable 3:
Using JavaScript and Leaflet.js a third map style was added to the earthquake map.



