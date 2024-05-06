# Rodanthe Shoreline Erosion
This project is an interactive map showing the change in shoreline location in Rodanthe, on Hatteras National Seashore on the Outer Banks of North Carolina.
It is intended as a supplement for [this AP article](https://apnews.com/article/environment-north-carolina-national-park-service-950b7804ae04d5798665429cc5afa226).
It uses the [LeafletJS](https://leafletjs.com/) library to visualize data, which was manually traced from imagery provided by NC OneMap.

Building and shoreline layers were traced in QGIS from imagery provided by [NC OneMap](https://www.nconemap.gov/pages/imagery), the buildings were orthagonalized, and both were exported to GeoJSON for use in Leaflet.