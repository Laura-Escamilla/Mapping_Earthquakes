# Mapping_Earthquakes

## Overview of the Project

For this Project we created interactive maps using GeoJSON data related to earthquakes around the world. Our purpose is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

We used JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. Then with the help of Leaflet library we plotted the data on a Mapbox map through an API request and created interactivity for the earthquake data.

## Results

The interactive map we created show the earthquakes around the world in the past seven days, we can see them in different color and size of the marker according to its magnitude, we added the major earthquakes data (the ones above 5 of magnitude) and, finally added the tectonic plates data to the map. In the image below we can see how our map looks like:

<img width="442" alt="Mapping_Earthquakes" src="https://user-images.githubusercontent.com/113747210/211952150-065ff9f4-3d6e-46ff-bbdf-15e80a244402.png">

## Summary

As we can see we can interact with the map and choose if we want to see only the major earthquakes, the tectonic plates or all of them in the map. Also, we added three different views of the map that also we can change, we have the street view which is shown when we first load the web page, then we can select the satellite view and finally a dark map.
