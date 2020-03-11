# Leaflet - USGS-Earthquake-Analysis

#### Background

![1-Logo](Images/1-Logo.png)

 The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The goal of this project was to use JavaScript to present an interactive map visualization of USGS earthquake data within a web page. Since the baseline data was provided in GeoJSON format, Leaflet was used to import and process the data, as well as generate the required visualization.

#### Questions

1. What are the locations and magnitudes of all earthquake events in the last twenty-four hours?

#### Datasets

https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_day.geojson

#### Tasks

1. Import the GeoJSON data.
2. Extract the location, magnitude, and timestamp of each earthquake event.
3. For each earthquake event, create a pop-up box with the above information.
4. For each earthquake event, create a circle marker whose size and color are proportional to the event's magnitude.
5. Import four map layers (satellite, outdoors, dark, light) from the Mapbox API.
6. Link the map layers, circle markers, and pop-up boxes together to create the interactive map.
7. Create a legend for the circle marker color scale and add it to the interactive map.

#### Results




