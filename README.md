# Open-Street-Map-Exploration
 Repository to explore osm python tools and learn about pulling data from osm and contributing programatically.

## OSMnx

OSMnx is a Python package that lets you download geospatial data from OpenStreetMap and model, project, visualize, and analyze real-world street networks and any other geospatial geometries. You can download and model walkable, drivable, or bikeable urban networks with a single line of Python code then easily analyze and visualize them. You can just as easily download and work with other infrastructure types, amenities/points of interest, building footprints, elevation data, street bearings/orientations, and speed/travel time.
- [OSMnx Github](https://github.com/gboeing/osmnx/tree/981ff1875bb9cc6c3575a87a1e42e59f5cc9f7d3)
- [OSMnx Docs](https://osmnx.readthedocs.io/en/stable/)
- [NetworkX Docs](https://networkx.org/)

## PYROSM

Pyrosm is a Python library for reading OpenStreetMap from Protocolbuffer Binary Format -files (.osm.pbf) into Geopandas GeoDataFrames. Pyrosm makes it easy to extract various datasets from OpenStreetMap pbf-dumps including e.g. road networks, buildings, Points of Interest (POI), landuse, natural elements, administrative boundaries and much more. Fully customized queries are supported which makes it possible to parse any kind of data from OSM, even with more specific filters.

Pyrosm is easy to use and it provides a somewhat similar user interface as OSMnx. The main difference between pyrosm and OSMnx is that OSMnx reads the data using an OverPass API, whereas pyrosm reads the data from local OSM data dumps that are downloaded from the PBF data providers (Geofabrik, BBBike). This makes it possible to parse OSM data faster and make it more feasible to extract data covering large regions.
- [PYROSM Github](https://github.com/HTenkanen/pyrosm)
- [PYROSM Docs](https://pyrosm.readthedocs.io/en/latest/)


## Overpass API
- [Overpass API Github](https://github.com/mvexel/overpass-api-python-wrapper)
- [Overpass API Docs](https://python-overpy.readthedocs.io/en/latest/)
- [Overpass API OSM Wiki](https://wiki.openstreetmap.org/wiki/Overpass_API)

## OSMPythonTools
- [OSMPythonTools Github](https://github.com/mocnik-science/osm-python-tools)
- [OSMPythonTools Docs](https://github.com/mocnik-science/osm-python-tools/tree/master/docs)
- [OSMPythonTools OSM Wiki](https://wiki.openstreetmap.org/wiki/OSMPythonTools)