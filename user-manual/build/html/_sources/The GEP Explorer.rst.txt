The GEP Explorer
============================

Placeholder 1
******************************************

*  Deserunt magna ad sit duis commodo irure dolor sint qui tempor. Deserunt et sint nostrud duis voluptate irure pariatur amet anim nostrud fugiat cupidatat. Tempor ipsum nulla sunt tempor cupidatat ipsum quis ut aliqua do ut anim ullamco. Cupidatat elit quis mollit cupidatat amet labore consequat est consectetur elit sint labore exercitation. Officia fugiat commodo do ullamco et est.


+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| #  | Dataset                   | Type            | Description                                                                     |
+====+===========================+=================+=================================================================================+
| 1  | Population density &      | Raster          | Spatial identification and                                                      |
|    | distribution              |                 | quantification of the current (base year) population. This dataset sets the     |
|    |                           |                 | basis of the ONSSET analysis as it is directly connected with the electricity   |
|    |                           |                 | demand and the assignment of energy access goals.                               |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 2  | Administrative boundaries | Raster          | Includes information (e.g. name) of the country(s) to be modelled and           |
|    |                           |                 | delineates the boundaries of the analysis.                                      |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 3  | Existing grid network     | Line shapefile  | Used to identify and spatially calibrate the currently                          |
|    |                           |                 | electrified/non-electrified population.                                         |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 4  | Substations               | Point shapefile | Current Substation infrastructure used to identify                              |
|    |                           |                 | and spatially calibrate the currently electrified/non-electrified               |
|    |                           |                 | population. It is also used in order to specify grid extension suitability.     |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 5  | Power plants              | Point shapefile | Current/Future power plant infrastructure                                       |
|    |                           |                 | used                                                                            |
|    |                           |                 | to,identify and spatially calibrate the                                         |
|    |                           |                 | currently electrified/non-electrified population. It is also used in order to   |
|    |                           |                 | specify grid extension suitability.                                             |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 6  | Mines & Queries           | Point shapefile | Being very important in                                                         |
|    |                           |                 | electrification processes, mines are usually used                               |
|    |                           |                 | in order to specify grid extension suitability.                                 |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 7  | Roads                     | Line shapefile  | Current Road infrastructure                                                     |
|    |                           |                 | used                                                                            |
|    |                           |                 | to,identify and spatially calibrate the                                         |
|    |                           |                 | currently electrified/non-electrified population. It is also used in order to   |
|    |                           |                 | specify grid extension suitability.                                             |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 8  | Planned grid network      | Point shapefile | Represents the future plans for the                                             |
|    |                           |                 | extension of the national electric grid. It also includes extension to          |
|    |                           |                 | current/future substations, power plants, mines and queries.                    |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 9  | Nighttime lights          | Raster          | Dataset used to,identify and spatially calibrate the                            |
|    |                           |                 | currently electrified/non-electrified population.                               |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 10 | GHI                       | Raster          | Provide information                                                             |
|    |                           |                 | about                                                                           |
|    |                           |                 | the Global Horizontal Irradiation (kWh/m2/year)                                 |
|    |                           |                 | over an area. This is later used to identify the availability/suitability of    |
|    |                           |                 | Photovoltaic systems.                                                           |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 11 | Wind speed                | Raster          | Provide information                                                             |
|    |                           |                 | about                                                                           |
|    |                           |                 | the wind velocity (m/sec) over an area. This is later used to identify the      |
|    |                           |                 | availability/suitability of wind power (using Capacity factors).                |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 12 | Hydro power potential     | Point shapefile | Points showing potential mini/small                                             |
|    |                           |                 | hydropower potential. Dataset developed by KTH dESA                             |
|    |                           |                 | including environmental, social and topological restrictions                    |
|    |                           |                 | and provides                                                                    |
|    |                           |                 | power availability in each identified point. Other sources can be used but      |
|    |                           |                 | should also provide such information to reassure the proper model function.     |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 13 | Travel time               | Raster          | Visualizes spatially the travel                                                 |
|    |                           |                 | time required to reach from any individual cell to the closest town with        |
|    |                           |                 | population more than 50,000 people.                                             |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 14 | Elevation Map             | Raster          | Filled DEM maps are use in a number                                             |
|    |                           |                 | of processes                                                                    |
|    |                           |                 | in                                                                              |
|    |                           |                 | the analysis (Energy potentials, restriction zones, grid extension suitability  |
|    |                           |                 | map etc.).                                                                      |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 15 | Slope                     | Raster          | A sub product of DEM, used in                                                   |
|    |                           |                 | forming restriction zones and to specify grid extension suitability.            |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+
| 16 | Land Cover                | Raster          | Land cover maps are use in a number                                             |
|    |                           |                 | of processes                                                                    |
|    |                           |                 | in                                                                              |
|    |                           |                 | the analysis (Energy potentials, restriction zones, grid extension suitability  |
|    |                           |                 | map etc.).                                                                      |
|    |                           |                 |                                                                                 |
+----+---------------------------+-----------------+---------------------------------------------------------------------------------+


Placeholder 2
*****************

Place holder 3
++++++++++++++++++++

**The GEP Explorer** deserunt magna ad sit duis commodo irure dolor sint qui tempor. Deserunt et sint nostrud duis voluptate irure pariatur amet anim nostrud fugiat cupidatat. Tempor ipsum nulla sunt tempor cupidatat ipsum quis ut aliqua do ut anim ullamco. Cupidatat elit quis mollit cupidatat amet labore consequat est consectetur elit sint labore exercitation. Officia fugiat commodo do ullamco et est.'

`This site <http://www.koalastothemax.com/>`_ deserunt magna ad sit duis commodo irure dolor sint qui tempor. Deserunt et sint nostrud duis voluptate irure pariatur amet anim nostrud fugiat cupidatat.

Placeholder 3
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++

+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Source                     | Type                | Link                                                                                                                                      |
+============================+=====================+===========================================================================================================================================+
| Penn                       | World per region    | http://guides.library.upenn.edu/content.php?pid=324392&sid=2655131                                                                        |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| MIT                        | World per region    | http://libguides.mit.edu/c.php?g=176295&p=1161383                                                                                         |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| EDEnextdata                | World per region    | https://www.edenextdata.com/?q=content/global-gis-datasets-links-0#Population%20Infrastructure%20Topography%20and%20Administration%20Data |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Stanford                   | World per region    | https://lib.stanford.edu/GIS/data                                                                                                         |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| GIS Lounge                 | Finding GIS data    | http://www.gislounge.com/data-and-gis-resources/                                                                                          |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| World Countries            | Different countries | http://www.gislounge.com/data-and-gis-resources/                                                                                          |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| dragons8mycat              | Different countries | https://dragons8mycat.wordpress.com/gis-data-sources/                                                                                     |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| rtwilson                   | Different types     | http://freegisdata.rtwilson.com/                                                                                                          |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Planet OSM                 | Different types     | http://planet.osm.org/                                                                                                                    |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Berkeley                   | Different types     | http://gif.berkeley.edu/resources/data_subject.html                                                                                       |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Kings College              | Different types     | http://www.policysupport.org/waterworld                                                                                                   |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| CSRC                       | Different types     | http://rslab.sr.unh.edu/gdatalinks.html                                                                                                   |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Data Discovery Center      | Different types     | http://ddc.unh.edu/                                                                                                                       |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Spatial Hydrology          | Different types     | http://www.spatialhydrology.com/datawarehouse.html                                                                                        |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+
| Africa Information Highway | Different types     | http://dataportal.opendataforafrica.org/                                                                                                  |
+----------------------------+---------------------+-------------------------------------------------------------------------------------------------------------------------------------------+

Placeholder 4
--------------

+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| Coverage                        | Type                         | Resolution                                                          | Year       | Source                         | Link                                                         |
+=================================+==============================+=====================================================================+============+================================+==============================================================+
| World                           | Coast Lines, oceans          | Physical vectors, ESRI shapefiles, GeoTIFF (1:10, 1:50 and 1:110 m) | 2015       | Natural Earth                  | http://www.naturalearthdata.com/downloads/                   |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| World                           | Climate data                 | 30 arc seconds and 2.5/5/10 arc minutes                             | na         | WorldClim                      | http://www.worldclim.org/                                    |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| World/USA                       | Climate change scenarios     | various                                                             | na         | na                             | https://gisclimatechange.ucar.edu/                           |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| World/Australia                 | Water and Landscape Dynamics | 0.05 to 1 degrees                                                   | 1979-2012  | Australian National University | http://www.wenfo.org/wald/data-software/                     |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| Open Street Map (OSM) - Osmosis | osm.pbf                      | depending on mirror source                                          | up to date | NOAA                           | http://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html      |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| Nighttime lights                | Raster file                  | 0.0083 degrees                                                      | 1992-2013  | na                             | https://www.ngdc.noaa.gov/eog/dmsp/downloadV4composites.html |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| Africa information Highway      | various                      | vectors                                                             | various    | AfDB                           | http://dataportal.opendataforafrica.org/                     |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+
| World                           | Cliamte data                 | various                                                             | various    | Oregon State University        | http://globalclimatedata.org/                                |
+---------------------------------+------------------------------+---------------------------------------------------------------------+------------+--------------------------------+--------------------------------------------------------------+

Placeholder 5
--------------------------------------------------------

.. note::

    * Vestibulum tortor quam, feugiat vitae, ultricies eget, tempor sit amet, ante.

    * Donec eu libero sit amet quam egestas semper. Aenean ultricies mi vitae est.

    * Mauris placerat eleifend leo. Quisque sit amet est et sapien ullamcorper pharetra. Vestibulum erat wisi, condimentum sed, commodo vitae, ornare sit amet, wisi.

    * Aenean fermentum, elit eget tincidunt condimentum, eros ipsum rutrum orci, sagittis tempus lacus enim ac dui. Donec non enim in turpis pulvinar facilisis.