# Cykelolyckor_jonkoping

Detta är koden till en webbkarta för att illustrera antaler och densiteten av cykelolyckor från utdrag från Transportstyrelsens databas STRADA.
Utdrag får man i excelformat som jag tvättat och konverterat från SWEREF99TM-koordinater till WGS84 i geojson-format så att det fungerar i universella webbaserade GIS såsom OpenLayers och Leaflet/MapBox.
I denna lösning har jag använt mig av Leaflet/Mapbox och ett antal plugin såsom Mapbox Heatmap from markers (https://www.mapbox.com/mapbox.js/example/v1.0.0/leaflet-heat-markers/) och Leaflet Hash (https://www.mapbox.com/mapbox.js/example/v1.0.0/leaflet-hash/).
