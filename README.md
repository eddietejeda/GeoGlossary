GeoGlossary
===========

# Interface and Interaction
These are generally Javascript libraries
Source:http://gis.stackexchange.com/questions/8032/comparison-of-javascript-mapping-libraries

#### Leaflet
Becoming the standard for many new projects (popular with Code for America fellows). Leaflet is lightweight and contains the majority of what people need for mapping, and is a great choice for majority of developers.  It is still a fairly young project.

#### ModestMaps
A small, extensible mapping library. It provides a core set of features in a tight, clean package with plenty of hooks for additional functionality. The project is supported by Stamen, Bloom and MapBox It is very modest and lightweight, meaning it has very little features out of the box.  But the architecture is a solid base to build on.

#### OpenLayers
Extensive documentation and a good amount of functionality plus the ability to use different map providers. The most solid and mature open source mapping library, but this has led to a lot of legacy code and weird APIs.  Can handle a lot of different sources, but most mapping does not require all this functionality.

#### Mapquery
The MapQuery project has the very worthwhile goal of combining OpenLayers and jQuery. The base functionality is there but the project is still quite young.

#### Mapstraction
Makes things very simple, especially working with multiple basemap providers. However it is still a work in progress and the functionality is lacking in places, as is the documentation.
        Though the idea of using one API for multiple libraries is kind of cool, there is very little use case of using multiple mapping libraries on a single site.

#### deCarta
Has a mobile and desktop javascript - first is HTML5/CSS3 compliant and the second has more browser compatibility. Source code provided. Friendliest developer terms for a commercial API. You are allowed to brand the map and there are several different map styles. You can choose NAVTEQ or OSM data. They also have several Mobile APIs as well.

#### Polymaps
Makes it very easy to composite raster and vector data from many different sources. Lets you easily add your own colouring, grouping, and interaction. Runs quickly, manages background tile loading well, and is only 30k of Javascript. SVG based and only runs in new browsers, otherwise this is a great library.

#### Jump
jump is a light weight maps library that works on its own, meaning, it is not a wrapper for OpenLayers or GoogleMaps API. Currently it is under development, but a lot of essential features work well.

#### Google Maps
#### Microsoft Virtual Earth
#### MapQuest
#### Yahoo Map API's
#### Cloudmade


# Interaction Middleware
These are libraries that consolidate different interaction layers

#### Wax
This is an library abstraction. It makes it easier to use APIs like Modest Maps and Leaflet, and documents, from the very start, the basics of web maps.
        Wax is mostly geared at making the Mapbox suite of tools (ie MBTiles) easier to manage.  It does provide some general tools as well.

# Data and Tile Formats

#### Vector formats
Formats like lines, points, polygons.

#### GeoJSON
Vector based data in the delicious JSON format.

#### KML
Google supported way of describing vector data

#### WKT
A way of describing vector data in text, not actually a feed.

#### OpenStreetMap (OSM)
OSM manages its data in a specific way and most people use PostGIS to work with it.

#### Raster formats
Raster formats are formats where aggregate formats, like representing an area with a specific 
color in a pixel, ie image sets.

#### XYZ tiles
This is how OSM provides its tile sets

#### MBTiles
an SQLlite based way of managing tiles and UTFGrid data.

# Tile Servers
#### Tilestache
TileStache is a Python-based server application that can serve up map tiles based on rendered geographic data.

####TileCache
TileStache is a Python-based server application that can serve up map tiles based on rendered geographic data.

#### Tilestream
A high-performance map tile server powered by MBTiles files



# Hosted Mapping Services

#### Mapbox
MapBox is an alternative to Google Maps powered by high-quality open data from OpenStreetMap. MapBox is really a hosting platform for MBTiles. The free tier is not very useful, but the $5/month is good enough for one or two maps Starting to add functionality, like Cloudmade, to make your own tilesets based on OpenStreetMap.
        
#### CloudMade
CloudMade provides you with access to a range of innovative tools and APIs that allow you to make the most of OpenStreetMap map data.
(with a free account) You can create custom OpenStreetMap based tiles, changing colors and styles, all within a web editor.

#### CartoDB
allows you to put your data on top of rich base layers. Use Google Maps, Mapbox tiles or Open Street Maps. You can even create maps without background if you want. CartoDB integrates with all major mapping and visualization engines through its mapping API.

# Tile Editors
These applications allow you to edit the styles of maps tiles.

#### TileMill
TileMill is an application for making maps.
#### Arc?

#### Fusion Tables?

# Map Renderers
These are low level libraries that users rarely have to interact with

#### Mapnik
Mapnik turns data like PostGIS, shapefiles, and styling definitions, like Carto, into different data formats, like MBTiles, XYZ tile sets, etc.
#### Arch? 

# Geo Server Applications

#### ArcGIS Server
#### Quantum GIS
#### GRASS GIS
#### GeoDjango
(this is really a wrapper around PostGIS/GEOS/GDAL for django)zx
#### GEOS
This includes all the SQL spatial predicate functions and spatial operators
#### GeoIQ
QGIS is an official project of the Open Source Geospatial Foundation (OSGeo). It runs on Linux, Unix, Mac OSX, and Windows and supports numerous vector, raster, and database formats and functionalities.
#### GeoServer
GeoServer is an open source software server written in Java that allows users to share and edit geospatial data.
#### MapServer
MapServer is an Open Source platform for publishing spatial data and interactive mapping applications to the web. Originally developed in the mid-1990's at the …
#### MapInfo


# Databases
These are databases

#### PostGIS
PostGIS adds support for geographic objects to the PostgreSQL object-relational database. In effect, PostGIS "spatially enables" the PostgreSQL server, allowing it to be used as a backend spatial database for geographic information systems (GIS), much like ESRI's SDE or Oracle's Spatial extension
#### MongoDB
document-oriented NoSQL database system.
#### ArcGIS Database
#### MS SQL
#### Couch (geocouch)

# File Storage Formats

#### SHP/DBF
The Esri shapefile or simply a shapefile is a popular geospatial vector data format for geographic information systems software. It is developed and regulated by Esri as an open specification for data interoperability among Esri and other software products.
#### FileGDB
#### PersonalGDB
#### GeoJSON
#### Shapefiles
#### ArcGIS REST
#### GeoRSS
#### KML

# ShapeFile Editors

#### QGIS
#### uDIG

# Geoquery Utility

#### GDAL (OGR)
#### GUTGeo File Editor
Made my Max Ogdan

# Place Name Databases

#### GeoNames
geographical database with a search function, browsable maps, and downloadable data files
#### Factual
#### OpenCalais
