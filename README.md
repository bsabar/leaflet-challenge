# USGS Data Visualization Project

## Background
In this project, I'm tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet. The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world daily but need a meaningful way of displaying it. 

This project pulls data from the USGS GeoJSON feed to visualize and create map plots based on their longitude and latitude. It also includes data markers by color, and the higher the earthquakes in magnitude they appear larger, the greater the depth, the darker the color. It also includes popups to provide additional data about the earthquake. 

## Tools Used
- `HTML`
- `CSS`
- `Leaflet`
- `geojson API`
- `d3.js`

## Requirements Delivered

### Map
- TileLayer loads without error 
- Connects to `geojson API` using `D3` without error 
- Markers with a size corresponding to earthquake magnitude 
- A legend showing the depth and their corresponding color 

### Data Points 
- Data points scale with magnitude level 
- Data points' colors change with the depth level
- Each point has a tooltip with the Magnitude, location, and depth
- All data points load in the correct locations

### Optional 
- Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You must pull in this dataset and visualize it alongside your original data.
  
### References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse but Predictable. They were retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
