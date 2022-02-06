# Mapping_Earthquakes

## Project Overview 
In this project we help Basil and Sadhana create an earthquake map with different maps and overlays. They wanted to see the earthquake data in relation to teh tectonic plates' location on the earth, specifically the earthquakes with a magnitude greater than 4.5. 

## Results 

In order to gather the data and layouts for the maps we created a mapbox account to utilize their API. 
[mapbox.com](https://www.mapbox.com/)

Street View
![image](https://user-images.githubusercontent.com/92435456/152704090-7ca0a471-104e-417a-ab44-77cddbe0afc3.png)

Satillite and Dark View
![image](https://user-images.githubusercontent.com/92435456/152704112-df053388-1af5-4e43-87cd-3a559e9889e0.png)![image](https://user-images.githubusercontent.com/92435456/152704122-cee7f1db-90bd-48df-8108-b513a0476bdc.png)

As we can see, the closer earthquakes occur to the fault lines of the plates generally, the higher magnitude the earthquake. There are a few of higher magnitute earthquakes that further away from the fault lines but the large majority of them are along fault lines. 
## Resources 

- Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes above 4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), [Tectonic Plate GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0
