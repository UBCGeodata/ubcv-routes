UBC Vancouver Road/Path dataset
===============================

General Info
------------
* Dataset created Spring 2015.
* Current as of Summer 2016.
* Contains all roads, sidewalks, paths, trails, etc at UBC Vancouver campus.
* Data were created to enable multimodal routing.
* Simplified versions are provided for simpler routing or cartography.
* Click on the geojson files to preview them on Github.

Datasets
--------
### ubcv_routes_src
* contains all route segments
### ubcv_roads
* contains only route segments where ROAD_TYPE = Arterial, Collector, Local, Service
### ubcv_paths_sidewalks
* contains only route segments where ROAD_TYPE != Arterial, Collector, Local, Service
* Note: Many routes commonly used by pedestrians are service roads.
### ubcv_roads_simple
* just named roads on campus, for simpler maps and labels.


Files Provided
--------------
* Provided in geojson and file geodatabase formats.
* FGDB is ESPG:26910/UTM10N, geojson ESPG:4326

License
-------
* This data is made available under the Public Domain Dedication and License v1.0 whose full text can be found at: [http://www.opendatacommons.org/licenses/pddl/1.0/](http://www.opendatacommons.org/licenses/pddl/1.0/)




About
-----
* More information about UBC's geospatial data on GitHub can be found [here](https://github.com/UBCGeodata/opendata)
* There is some info about how to view and download data at the link above.
