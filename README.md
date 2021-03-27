## Mapping_Earthquakes

## Project Overview
Creating interactive maps that are easy to use is a necessary skill for someone in the data visualization field. 
Maps allows to explore, understand and make decisions about our work. In mapping earthquakes, we build our JavaScript skills and D3 library
to 
 - Create an interactive world map.
 - Use GeoJSON to host geographic information.

 GeoJASON data can be found in many apps such as Ride Sharing, Navigation and food delivery services, even the apps on our smart phone that allow
 to track the location, store and use a GeoJSON data. We will use geographical features such as
 - Point, which contain addresses and locations, like latitude and longitude coordinates.
 - LineStrings, which contain coordinates for the boundaries of streets, highways, travel routes, and tectonic plates.

 Using the knowledge of JavaScript and D3 library, we will traverse and retrieve GeoJSON earthquakes data and tectonic plate data 
 in order to populate a geographical map. For this, we also use a Leaflet library and the Mapbox API. 

Therefore,  we use the Leaflet.js Application Programming Interface (API) to do the following steps: 
   - Populate a geographical map with GeoJSON earthquake data from a URL
   - Display tectonic plate data with the LineStrings type.
   - Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter. 
   - each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.


## Resources
Software: [Visual Studio Code](https://code.visualstudio.com/), [JavaScript ES6](https://www.w3schools.com/Js/js_es6.asp) 

library: Leaflet and D3


## Summary
This project is summarized as follows, using JavaScript's Leaflet library along with the Mapbox API to create visualizations of earthquake data from the U.S. Geographical Survey:

1- Add tectonic plate data to the map 
 - Using d3.json() 
 - Adding the data using the geoJSON() layer 
 - Seting the tectonic plate LineString data to stand out on the map 
 - Adding the tectonic plate data to the overlay object with the earthquake data.

2- Add major earthquakes data
 - Using d3.json()
 - Using a color and set the radius of the circle based on the magnitude of earthquake
 - Adding a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON()

 3-  Add a third map style as a tile layer object to the main logic.js file and add the map variable to the base layer object.   
