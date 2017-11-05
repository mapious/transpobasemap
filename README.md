# transpobasemap

This repository contains the base map created for the final project. 

## GeoServer

[wms url](http://localhost:8080/geoserver/ceoas/wms?service=WMS&version=1.1.0&request=GetMap&layers=ceoas:ore_counties&styles=&bbox=-124.56670504390223,41.991794810535794,-116.46326242572455,46.23731681568611&width=768&height=402&srs=EPSG:4326&format=application/openlayers)
![oregon county](img/ceoas-ore_counties.png)

[wfs url](http://localhost:8080/geoserver/ceoas/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=ceoas:ore_counties&maxFeatures=50&outputFormat=application%2Fjson)
[geojson data](asset/ore_counties.geojson)


