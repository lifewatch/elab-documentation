---
layout: default
title: Web service description
nav_order: 3
---

# Description of the web services

The web services can also be used in a concatenated way, where the output of the first web service is the input for the next web service. This is demonstrated in the Use cases.

## Data validation and QC services

### Data format validation
The LifeWatch portal uses a specific standard data format based on Darwin Core and the OBIS Schema (see above). This service checks if the uploaded data file matches this standard LifeWatch data format.
### Show on map
This service generates a map based on Latitude and Longitude in the uploaded data file. The resulting map is available in the result report.
### Check OBIS file
This service checks if the uploaded data file matches the OBIS Schema (mandatory and missing fields), checks the format of the date and coordinates and checks if the observation points are located at sea or on land. This service also performs a WoRMS taxon match.

## EMODnet Biology 
### Number of observations in a 1000m radius around a point
Returns the number of observations in the Ocean Biodiversity Information System (OBIS) of taxon in a radius of 1000 meter around a point, based on Latitude and Longitude in the uploaded data file.

## ​​Geographical services - Administrative boundaries:
These web services return the name and code of administrative boundaries, such as EMODnet regions, Exclusive Economic Zones (EEZ), ICES Ecoregions, IHO Sea Areas, Intersect of the EEZ and IHO (Marine Regions), World Countries, and FAO Fishing Areas, based on Latitude and Longitude in the uploaded data file.​​

### Exclusive Economic Zone 
### FAO Fishing areas
### ICES Ecoregions
### IHO Sea areas
### Intersect of the EEZ and IHO
### World countries
Returns the country based on latitude and longitude

## Geographical services - Bathymetry:

### Bathymetry Southern Bight of the North Sea 
Returns the bathymetry for points in the Southern Bight of the North Sea (from the "Limited Atlas of the Belgian Part of the North Sea"), based on Latitude and Longitude in the uploaded data file.

### ​​GEBCO bathymetry 
Returns the bathymetry from the General Bathymetric Chart of the Oceans (GEBCO), based on Latitude and Longitude in the uploaded data file.

### MARSPEC: global marine bathymetrie (Resolution: 30 arc seconds) 
Returns the global marine bathymetry with a resolution of 30 arc seconds from the Ocean Climate Layers for Marine Spatial Ecology (MARSPEC), based on Latitude and Longitude in the uploaded data file.

## Geographical services - Biogeographical classification

### Large Marine Ecosystems of the World
### Longhurst Provinces
### Marine Ecoregions of the World
### Marine Provinces of the World
### Marine Realms of the World

## Geographical services - Environmental data
### Calcite (mean) [mol/m<sup>3</sup>]
### Chlorophyll A (maximum) [mol/m<sup>3</sup>]
### Chlorophyll A (mean) [mol/m<sup>3</sup>]
### Chlorophyll A (minimum) [mol/m<sup>3</sup>]
### Chlorophyll A (range) [mol/m<sup>3</sup>]
### Cloud fraction (maximum) [%]
### Cloud fraction (mean) [%]
### Cloud fraction (minimum) [%]
### Diffuse attenuation coefficient at 490 nm (maximum) [m<sup>-1</sup>]
### Diffuse attenuation coefficient at 490 nm (mean) [m<sup>-1</sup>]
### Diffuse attenuation coefficient at 490 nm (minimum) [m<sup>-1</sup>]
### Dissolved oxygen [ml/l]
### Nitrate 
### pH [no unit]
### Phosphate [µmol/l]
### Photosynthetically available radiation (maximum) [Einstein/m<sup>2</sup>/day]
### Photosynthetically available radiation (mean) [Einstein/m<sup>2</sup>/day]
### Salinity [PSS]
### Sea surface temperature (maximum) [Celsius]
### Sea surface temperature (mean) [Celsius]
### Sea surface temperature (minimum) [Celsius]
### Sea surface temperature (range) [Celsius]
### Silicate [µmol/l]

## Geographical services - Features
### Shoals (Belgian Continental Shelf)
Indicates if a given location in the Belgian Continental Shelf is situated on a shoal, based on Latitude and Longitude in the uploaded data file, and gives the name and group of the shoal.

## Geographical services - Protected areas
### Flemish Ecological Network 
Indicates if a given location is situated within the Flemish Ecological Network, based on Latitude and Longitude in the uploaded data file, and gives the type and name of the VEN-area. The Flemish Ecological Network (VEN) is a selection of valuable and sensitive natural areas in Flanders. The Flemish government gives priority to nature conservation and nature development in these areas.

## Geographical services - Total biological valuation:
### Terrestrial Biological Valuation (v22) 
Returns the terrestrial biological value of a location in the Flemish Region, based on Latitude and Longitude in the uploaded data file and the Biological Valuation Map (version 22). The Biological Valuation Map is a uniform field-driven survey of the land cover and vegetation in the Flemish Region.

### Marine Biological Valuation Map for the Belgian Part of the North Sea
Returns the total marine biological value of a location in the Belgian Continental Shelf, based on Latitude and Longitude in the uploaded data file and the Biological Valuation Map for the Belgian Continental Shelf (BWZee) produced in 2007.

## Marineregions gazetteer services

### Get lat-long by mrgid
Returns the latitude and longitude of the centroid and the preferred gazetteer name of a Marine Regions ID (MRGID), based on the MRGID in the uploaded data file.

### Get lat-long by name
Returns the latitude, longitude, matched name and the Marine Regions ID (MRGID) of a given gazetteer name in the uploaded data file.

### Get gazetteer name by lat-long
Returns the Marine Regions place name and the Marine Regions ID (MRGID) of the bounding box (radius 3) based on Latitude and Longitude in the uploaded data file.

### Get lat-long by accepted name
Returns the latitude, longitude, accepted name and the Marine Regions ID (MRGID) of a given gazetteer name in the uploaded data file.

## Other taxon services

### Get AphiaID World Register of Marine Species (WoRMS)
Returns the (first) exact matching AphiaID for a given taxon name, based on the ScientificName in the uploaded data file.

### Get GUID Pan-European Species Infrastructure 
The service returns the Globally Unique Identifier (GUID) from PESI for a given taxon name, based on ScientificName in the uploaded data file.

### Reverse taxon match by ITIS TSN 
Returns the Aphia record (scientific name, taxonomic status, etc.) based on the Taxonomic Serial Number (TSN) of the Integrated Taxonomic Information System (ITIS) in the uploaded data file.

### Reverse taxon match by AphiaID
Returns the Aphia record (scientific name, taxonomic status, etc.) based on the AphiaID of the World Register of Marine Species (WoRMS) in the uploaded data file.

## Taxon match services
### Pan-European Species directories Infrastructure (PESI)
The service matches your taxon list with the Pan-European Species directories Infrastructure database (PESI), based on the ScientificName in the uploaded data file. Website information : http://www.eu-nomen.eu/portal/webservices.php

### Paleobiology Database (PaleoDB)
The service matches your taxon list with the Paleobiology Database (PaleoDB), based on the ScientificName in the uploaded data file.

### Integrated Taxonomic Information System (ITIS)
The service matches your taxon list with the Integrated Taxonomic information System (ITIS), based on the ScientificName in the uploaded data file.

### Taxon match Global Names Index (GNI)
The service matches your taxon list with the Global Names Index (GNI), based on the ScientificName in the uploaded data file.

### Index Fungorum (IF)
The service matches your taxon list with the Index Fungorum (IF) database, based on the ScientificName in the uploaded data file.

### International Plant Names Index (IPNI)
The service matches your taxon list with the International Plant Names Index (IPNI), based on the ScientificName in the uploaded data file.

### World Register of Marine Species (WoRMS)
The service matches your taxon list with the World Register of Marine Species (WoRMS), based on the ScientificName in the uploaded data file.

### Taxon match Interim Register of Marine and Nonmarine Genera (IRMNG)
The service matches your taxon list with the Interim Register of Marine and Nonmarine Genera (IRMNG), based on the ScientificName in the uploaded data file.

### Catalogue of Life (CoL)
The service matches your taxon list with the Catalogue of Life (CoL), based on the ScientificName in the uploaded data file

## Taxon match services WoRMS Regional Species Databases

### Taxon match African Register of Marine Species (AfReMaS)
The service matches your taxon list with the African Register of Marine Species (AfReMaS), based on the ScientificName in the uploaded data file.

### Taxon match Belgian Register of Marine Species (BeRMS)
The service matches your taxon list with the Belgian Register of Marine Species (BeRMS), based on the ScientificName in the uploaded data file.

### Taxon match Register of Antarctic Marine Species (RAMS)
The service matches your taxon list with the Register of Antarctic Marine Species (RAMS), based on the ScientificName in the uploaded data file.

## Taxon match services WoRMS Thematic Species Databases

### Taxon match IOC-UNESCO Taxonomic Reference List of Harmful Micro Algae (HAB) 
The service matches your taxon list with the IOC-UNESCO Taxonomic Reference List of Harmful Micro Algae (HAB), based on the ScientificName in the uploaded data file.

### Taxon match World Register of Deep-Sea Species (WoRDSS)
The service matches your taxon list with the World Register of Deep-Sea Species (WoRDSS), based on the ScientificName in the uploaded data file.

### Taxon match World Register of Marine Introduced Species (WRIMS)
The service matches your taxon list with the World Register of Marine Introduced Species (WRIMS), based on the ScientificName in the uploaded data file.

### Taxon match World Register of marine Cave Species (WoRCS)
The service matches your taxon list with the World Register of marine Cave Species (WoRCS), based on the ScientificName in the uploaded data file.

## Taxon observations

### Number of observations of a marine taxon
Returns all observation points (latitude and longitude) in the Ocean Biodiversity Information System (OBIS) for a specific species, based on the ScientificNameID in the uploaded data file. Website information: http://www.iobis.org/geoserver/web/

### Taxon list of a certain region 
Returns a taxon list based on observations from the Ocean Biodiversity Information System (OBIS) for a certain region, based on the Marine Regions ID (MRGID) in the uploaded data file. Website information: http://www.iobis.org/geoserver/web/

### Occurence of a taxon is located within a known distribution record
The service verifies if the coordinates of the taxon observation in the uploaded data file are located within a distribution record of that taxon in WoRMS/Aphia. In the result report a map is available which shows the coordinates in the uploaded data file and the distribution records of the taxa in WoRMS/Aphia. Website information: http://marinespecies.org/aphia.php?p=webservice

## ​Tidal services:

### Calculate tidal reduction
Calculates tidal heights in NAP (Normaal Amsterdams Peil), GLLWS (Gemiddeld Laag LaagWater bij Springtij), and TAW (Tweede Algemene Waterpassing) based on Latitude, Longitude and EventDate in the uploaded data file. The calculations are based on the M2 tidal reduction algorithm and the water levels measured by the monitoring network Flemish Banks.
