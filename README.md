# Identifying the Impacts of Extreme Weather
### Description
This repository contains data and code for homework assignment 4 for EDS223 Geospatial, which focuses on identifying the impacts of extreme winter storms in the Houston, Texas area. 

### Contents
All code, comments, and outputs are in "extreme_weather.qmd".

The "data" folder contains all necessary data including remote sensing (satellite) imagery, 
The `ACS_2019_5YR_TRACT_48_TEXAS.gdb` folder contains 
The `VNP46A1` folder contains remote sensing data from NASA, covering the Houston area on 2021-02-07 and 2021-02-16 (before and after the storm).
The file `gis_osm_buildings_a_free_1.gpkg` contains the locations of buildings (including type) in the Houston area.
The file `gis_osm_roads_free_1.gpkg` displays the locations of Houston area roads (including type).

### Repository Structure
```{bash}
.
├── README.md
├── data
│   ├── VNP46A1
│   │   ├── VNP46A1.A2021038.h08v05.001.2021039064328.tif
│   │   ├── VNP46A1.A2021038.h08v06.001.2021039064329.tif
│   │   ├── VNP46A1.A2021047.h08v05.001.2021048091106.tif
│   │   └── VNP46A1.A2021047.h08v06.001.2021048091105.tif
│   ├── gis_osm_buildings_a_free_1.gpkg
│   └── gis_osm_roads_free_1.gpkg
└── extreme-weather.qmd

```

### Data Access
Data is housed locally in the repository.

VIIRS data (in `VNP46A1`) comes from the Visible Infrared Imaging Radiometer Suite (VIIRS) onboard the Suomi satellite.  It can be accessed through NASA’s Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC), at https://ladsweb.modaps.eosdis.nasa.gov.

The data in `gis_osm_buildings_a_free_1.gpkg` and `gis_osm_roads_free_1.gpkg` comes from OpenStreetMap (https://planet.openstreetmap.org), distributed through Geofabrik’s download sites (https://download.geofabrik.de).

### Authors
Oliver Witt

Original assignment by Ruth Oliver and Annie Adams

### References/Acknowledgements
This assingment was produced for a UCSB MEDS course taught by Annie Adams.  The original assignment was written by Ruth Oliver.

OpenStreetMap (building and road data):
OpenStreetMap. (n.d.). Planet OSM. https://planet.openstreetmap.org/ 

VIIRS Data (satellite imagery):
NASA. (n.d.). LAADS DAAC. NASA. https://ladsweb.modaps.eosdis.nasa.gov/ 


