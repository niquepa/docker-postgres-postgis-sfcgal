# PostgreSQL-PostGIS-sfcgal

expand on https://github.com/docker-library/postgres

includes :

* PostgreSQL 9.6
* PostGIS 2.3.0
* geos 3.5.0
* gdal 2.1.1
* proj 4.9.2
* cgal 4.6.3
* sfcgal 1.3.0

Use template `template_postgis` to create your databases with postgis / sfcgal enabled

You can also simply use : 
```
CREATE EXTENSION postgis;
CREATE EXTENSION postgis_topology;
CREATE EXTENSION postgis_sfcgal;
```

and from http://postgis.net/docs/postgis_installation.html#install_short_version
```
-- if you want to install tiger geocoder --
CREATE EXTENSION fuzzystrmatch;
CREATE EXTENSION postgis_tiger_geocoder;

-- address standardizer extension as well
CREATE EXTENSION address_standardizer;
```
