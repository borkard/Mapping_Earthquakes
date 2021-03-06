# Mapping Earthquakes

## Overview
This project involved using JavaScript, Leaflet, Mapbox, HTML and CSS to show GeoJSON USGS earthquake data on a map that displays all earthquakes from the past seven days.
The map was built using the Mapbox API and customized with different base layer map styles, overlays for the earthquake data, major earthquakes, and tectonic plates, markers for the earthquakes, and a legend for the magnitude of the earthquakes.

## Results
The image below shows the map of earthquakes around the world in the past seven days. The layer feature on the top right has options to switch the base layer to one of three different views (Street, Satellite, or Dark) and there are three overlays for Earthquakes, Tectonic Plates, and Major Earthquakes with a magnitude over 4.5. The three overlays can be toggled for any combination or view.

![earthquake_map](https://github.com/borkard/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/earthquake_map.png)

Pop-up circle markers were also added to mark where each of the earthquakes took place and will show the magnitude and location of the earthquakes when clicked. The radius of each circle is proportional to the size of the earthquake and the colors are also determined by the magnitude, as shown in the legend on the bottom right.

![popup_marker](https://github.com/borkard/Mapping_Earthquakes/blob/main/Earthquake_Challenge/images/popup_marker.png)
