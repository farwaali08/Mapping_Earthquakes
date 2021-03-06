# Mapping_Earthquakes

## OVERVIEW

This project features an interactive map of global seismic activity in relation to tectonic plate boundaries. The data for the map was sourced from the United States Geological Survey (USGS), who provides the most current data (Past 7 Days) in GeoJSON format.

The map displays the following datasets, and features 3 viewing options (Street, Satellite, and Dark):

* Current data for earthquakes of all magnitudes
* Current data for earthquakes with a magnitude >4.5
* Tectonic plate boundaries

The earthquake data is presented in accordance with each event's magnitude.

## TOOLS & RESOURCES

**SOFTWARE**

* JavaScript
* Leaflet
* Mapbox
* D3
* HTML/CSS

**DATA**

* Challenge Code: [challenge_logic.js](https://github.com/farwaali08/Mapping_Earthquakes/blob/7a3a870cdcd57f2902bccbc81eea7dcc7cd309e5/Earthquake_Challenge/static/js/challenge_logic.js)
* [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
* [Tectonic Plates GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
* [Major Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)

## MAPS

### STREET VIEW

![alt_text](https://github.com/farwaali08/Mapping_Earthquakes/blob/91584a7475f1e95b564836dc8ad593a07563dee8/Images/streets.png)

### SATELLITE VIEW

![alt_text](https://github.com/farwaali08/Mapping_Earthquakes/blob/91584a7475f1e95b564836dc8ad593a07563dee8/Images/satellite.png)

### DARK VIEW

![alt_text](https://github.com/farwaali08/Mapping_Earthquakes/blob/7864a61def44d8c68aaa454fe819e6e6bda4002d/Images/dark.png)

### USER PREFERENCE

The user may select or omit certain features on the map to best suit their preferences. In the example below, the "Tectonic Plates" layer has been de-selected, so that only the earthquake layers are visible. Pop-ups are included to provide information about each earthquake event.

![alt_text](https://github.com/farwaali08/Mapping_Earthquakes/blob/fd3d8c4c0dfb4d0f2c2ca765045b425124aa0a23/Images/pop-up.png)
