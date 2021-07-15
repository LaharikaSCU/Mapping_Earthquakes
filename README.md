# Mapping_Earthquakes

## Overview of project
### Purpose
 Map different magnitudes of earthquakes all over the world for the last seven days, thus help visualize the difference.

### Tasks
This project uses a URL of GeoJSON earthquake data from the USGS website and retrieves geographical coordinates and the magnitudes of earthquakes for the last seven days and maps the data.

### Approach
 
 High level approach:
 - use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data.
 - mapbox provides custom maps for websites and applications such as Strava, Facebook, the Financial Times, The Weather Channel, Snapchat, and Instacart.
 - setup a mapbox account, generate an api token key.
 - using the Leaflet library, plot the data on to a Mapbox map through an API request and create interactivity for the earthquake data.
 - Lastly, add multiple maps and overlay's with different GeoJSON data ( major earthquakes, tectonic plates) with a custom legend.
 
## Resources
* Data Source:
    * earthquake data (GeoJSON)          : https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
    * Major earthquake data (GeoJSON)    : https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
    * Techtonic boundaries.              : https://github.com/fraxen/tectonicplates/blob/master/GeoJSON/PB2002_boundaries.json
* Data Tools:  Visual Studio Code 1.57.0, JSON Viewer
* Software: ES6+ (Javascript), Leaflet.js
