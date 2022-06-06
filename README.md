# Mapping Earthquakes

## Project Overview

The overview of this project is to create an interactive map that is easy to use. With the use of JavaScript and the D3 library we created an interactive world map. We used GeoJSON to host geographical information. The geographical features that are used within this map are points, linestrings, and polygons. An additional feature that was used is a non-spatial attribute, such as magnitude of an earthquake. Using JavaScript and the D3 library we retrieved GeoJSON earthquake data and tectonic plate data in order to populate a geographical map. 

## Project Purpose

The purpose of this project is to provide a visualization tool to visualize earthquake and tectonic plate data with information in the past week. 

## Results

Using JavaScript and the D3 library we were able to create an earthquake and tectonic plate map with three different map overlays: Street, Satellite and Dark. Another feature within the map is the toggle feature. The user is able to toggle between three different sources of data: Earthquakes, Tectonic Plates, and Major Earthquake. 

### Three Viewing Options:

1. Street
2. Satellite
3. Dark

![Screen Shot 2022-06-05 at 10 01 02 PM 2](https://user-images.githubusercontent.com/99099706/172087402-000e4eaa-dee3-4a78-8fa0-3548e57dbee9.png)
### Three Layers Options:

1. Earthquakes
2. Tectonic Plates
3. Major Earthquakes

![Screen Shot 2022-06-05 at 10 04 05 PM 2](https://user-images.githubusercontent.com/99099706/172087656-e63036d9-a4b4-4810-9666-e9836f9e761d.png)

## Summary

In order to populate the map an API was called to retrieve GeoJSON earthquake data and tectonic plate data. Then using the Leaflet library, we were able to plot the point data, linestring data, polygon data, and our non-spatial attributes (magnitude size). The user is then able to toggle between the different viewing and layer options. By being able to toggle between earthquake and tectonic plate data, the user is able to view the correlation of major earthquakes location with the tectonic plate location. 
