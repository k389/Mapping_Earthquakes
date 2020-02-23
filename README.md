# Mapping_Earthquakes
JavaScript, GeoJSON

# Project Overview/Challenge
- Use Leaflet JavaScript library and Mapbox to import different maps.
- Use GeoJSON to populate a map with earthquake data and tectonic plate data.
- Learn how to use GitHub branch method to collaborate with others in a project. 

# Resources
- Data Source: "https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson", "https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json"
- Software: Visual Studio Code, 1.40.2., Google Chrome, JavaScript, Leaflet library.

# Summary
- Used VS Code to create JavaScript, HTML, CSS files to deploy Earthquake data on a map.
- Created base layer to hold three different maps (street, satellite and light).
- Use Leaflet and Mapbox to import the three maps into the JavaScript.
	- Customize the map to choose between the three maps and also choose between earthquake data or tectomic plates data or both. 
		- Give the user choice which data to choose using overlays and base layers.
- Use the Earthquake GeoJson data to populate the map with earthquake data.
	- indicate the earthquake data with markers on the map using Leaflet marker method.
	- colorcode the markers to indicate the intencity of the earthquakes.
	- add a leged to show the color range of the earthquakes.
	- populate the earthquake data on all three maps.
	- add a popup to label each marker with the earthquake information (magnitute of the earthquake and the location).
- Use a GeoJSON file to import tectonic plates data onto the maps.
	- populate the data on all three maps. 
	- add a popoup to label the name of the tectonic plates
	- style the lines to show on all the maps with bright color.

