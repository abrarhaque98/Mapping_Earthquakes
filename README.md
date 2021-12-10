# Mapping_Earthquakes

## Overview of the Mapping Earthquakes Challenge
In this Challenge, I've assumed the role of a data visualization specialist for the Disaster Reporting Network. I am tasked with creating interactive maps of earthquake data from around the world. Thusfar, the map I've created includes two different maps and the earthquake overlay. Now, I have to represent the earthquake data in relation to the tectonic plates’ location on the earth (Deliverable 1), depict an additional overlay layer of earthquakes with a magnitude greater than 4.5 on the map (Deliverable 2), and create a third map (Deliverable 3).

For Deliverable 1, I added tectonicPlates to the overlays object, and used d3.JSON to call the Tectonic Plate geoJSON data and plot it as a layer.

For Deliverable 2, I used a different geoJSON file from USGS that contained earthquakes with a magnitude greater than 4.5. I added majorEarthquakes to the overlays object, used d3 to call the data, and styled and plotted it as a layer in a similar manner that I did all earthquakes. To color these earthquakes, I assigned yellow for earthquakes less than 5, orange for earthquakes between 5 and 6, and red for earthquakes greater that 6. The image below shows that this layer works successfully, and does not depict the other smaller earthquakes.

For Deliverable 3, I created a third map called "Dark", creating a new tileLayer and adding it to the base layer. It appears in the top corner for users to select.

