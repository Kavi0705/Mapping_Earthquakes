# Mapping_Earthquakes
## Purpose
The purpose of this analysis is to visually show the differences between the magnitudes of earthquakes all over the world for the last 7 days. 

## Approach
The analysis was accomplished by using JavaScript and the D3.js library in order to retrieve the coordinates and magnitudes of the earthquakes from GeoJSON data. The Leaflet library was used to plot the data on a Mapbox map through an API request, and to create interactivity for the earthquake data.

## Results

Earthquake data for the past 7 days was plotted on a Mapox map via an API request. Along with the earthquakes being plotted, tectonic plate data is added as a second layer group as well as an overlay object. Color and width are added to the tectonic plate lines via a geoJSON() layer. Below is an image of the map in Streets View.

<img width="1350" alt="Plates_Streets view" src="https://user-images.githubusercontent.com/93743169/162872106-9a10961d-6591-4b62-8e58-fb1ac8d6158e.png">

In the second step, the following was added to the map: color and radius of the circle markers based on magnitude of earthquake, and a popup marker for each earthquake that displays the magnitude and location of the earthquake. The image below displays this information in a Satellite View.

<img width="1351" alt="Popup_Satellite View" src="https://user-images.githubusercontent.com/93743169/162872574-7ffb10c0-091c-4d3c-87f6-b589db1094b6.png">

Finally, using the option from the Mapbox styles, a third map style (dark) was added as a tile layer object.

<img width="1361" alt="Dark view" src="https://user-images.githubusercontent.com/93743169/162872921-974e9aa3-e7cd-4ddc-b99e-b173bbb26b45.png">
