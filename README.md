﻿# Eatonville
This repository was created as part of a master's capstone project. 

Mapbox Studio is the Mapbox application for managing geospatial data. Like ArcGIS Online, it allows the user to upload, edit their data to customize as they see fit. However, Mapbox requires a learning curve when using its platform. It requires knowledge of HTML, JavaScript, and CartoCSS to fully utilize all its capabilities. To get started, an access token: a short code that allows developers use of Mapbox account’s capabilities. It can be used in their interactive mapping libraries, Python and JavaScript SDKs and against their REST APIs. 

Utilizing the free account of Mapbox, issues arise due to the large data file for upload. To elevate this issue, the data format was converted to a comma separated values (csv) file. It was then uploaded to Mapbox datasets which renders the data as a point feature. Once the dataset is added and edited, it then needs to be exported to a tileset. Tileset is a collection of raster or vector data that is broken down to optimize faster rendering. The “light” tileset was selected to style both datasets; publish and share to finish. Figure 7 shows the steps to create a Mapbox map. 

Mapbox GL JS, a JavaScript library that utilize WebGL to render maps interactive was then applied. Mapbox provides very useful examples and documentation to allow users to replicate and create interactive maps to their liking. 
