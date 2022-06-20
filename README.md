# Mapping Earthquakes 
## Overview of Project
> Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

1. ***Deliverable 1***: Add Tectonic Plate Data
2. ***Deliverable 2***: Add Major Earthquake Data
3. ***Deliverable 3***: Add an Additional Map
4. ***Deliverable 4***: A written report on the Mapping Earthquakes analysis [`README.md`](https://github.com/DataJew/Mapping_Earthquakes/). 
 
# Deliverable 1:  
## Add Tectonic Plate Data
### Deliverable Requirements:
Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add tectonic plate data using `d3.json()`, add the data using the `geoJSON()` layer, set the tectonic plate `LineString` data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.

Your final map should look similar to the following image:

![name-of-you-image](https://github.com/DataJew/Mapping_Earthquakes/blob/main/Resources/Images/deliverable1.png)



1. The tectonic plate data is added as a second layer group.
2. The tectonic plate data is added to the overlay object.
3. The `d3.json()` callback is working and does the following:
  - The tectonic plate data is passed to the `geoJSON()` layer
  - The `geoJSON()` layer adds color and width to the tectonic plate lines
  - The tectonic layer group variable is added to the map
4. The earthquake data and tectonic plate data displayed on the map when the page loads.


# Deliverable 2:  
## Add Major Earthquake Data
### Deliverable Requirements:
Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add major earthquake data to the map using `d3.json()`, and a color and set the radius of the circle based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, `geoJSON()`.

Your final map should look similar to the following image:

![name-of-you-image](https://github.com/DataJew/Mapping_Earthquakes/blob/main/Resources/Images/deliverable2.png)



1. The major earthquake data is added as a third layer group.
2. The major earthquake data is added to the overlay object.
3. The `d3.json()` callback is working and does the following:
  - Sets the color and diameter of each earthquake.
  - The major earthquake data is passed to the `geoJSON()` layer.
  - The **geoJSON()** layer creates a circle for each major earthquake, and adds a popup for each circle to display the magnitude and location of the earthquake
  - The major earthquake layer group variable is added to the map
4. All the earthquake data and tectonic plate data are displayed on the map when the page loads and the datasets can be toggled on or off.


# Deliverable 3:  
## Add an Additional Map
### Deliverable Requirements:
Using your knowledge of JavaScript and Leaflet.js add a third map style to your earthquake map.

Your final map should look similar to the following image:

![name-of-you-image](https://github.com/DataJew/Mapping_Earthquakes/blob/main/Resources/Images/deliverable3.png)



1. A third map tile layer is created.
2. The third map is added to the overlay object.
3. All the earthquake data and tectonic plate data are displayed on the all maps of the webpage.

 

# Deliverable 4:  
A written report on the Mapping Earthquakes analysis [`README.md`](https://github.com/DataJew/Mapping_Earthquakes/). 


1. **A README.md that describes the purpose of the repository. Although there is no graded written analysis for this challenge, it is encouraged and good practice to add a brief description of your project.**

