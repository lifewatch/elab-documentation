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

## Geographical services - Biogeographical classification:

### Large Marine Ecosystems of the World
### Longhurst Provinces
### Marine Ecoregions of the World
### Marine Provinces of the World
### Marine Realms of the World

Geographical services - Environmental data:

These web services return environmental data from Bio-ORACLE (Ocean Rasters for Analysis of Climate and Environment): a global environmental dataset for marine species distribution modeling, based on Latitude and Longitude in the uploaded data file. Available parameters include: Sea Surface Temperature (minimum, maximum, mean, range), Salinity (mean), Chlorophyll-a (minimum, maximum, mean, range), Photosynthetically Available Radiation​ (minimum, mean),  pH (mean), Calcite Concentration (mean), Dissolved Oxygen (mean), Silicate (mean), Nitrate (mean), Phosphate (mean), Diffuse Attenuation​ (minimum, maximum, mean), and Cloud Cover (minimum, maximum, mean).

Geographical services - Features:

Shoals (Belgian Continental Shelf): Indicates if a given location in the Belgian Continental Shelf is situated on a shoal, based on Latitude and Longitude in the uploaded data file, and gives the name and group of the shoal.





Taxon observations:

Number of observations of a marine taxon: Returns all observation points (latitude and longitude) in the Ocean Biodiversity Information System (OBIS) for a specific species, based on the ScientificNameID in the uploaded data file.


Taxon list of a certain region: Returns a taxon list based on observations from the Ocean Biodiversity Information System (OBIS) for a certain region, based on the Marine Regions ID (MRGID) in the uploaded data file.

Taxon services:

Get AphiaID World Register of Marine Species (WoRMS): Returns the (first) exact matching AphiaID for a given taxon name, based on the ScientificName in the uploaded data file.
Reverse taxon match by ITIS TSN: Returns the Aphia record (scientific name, taxonomic status, etc.) based on the Taxonomic Serial Number (TSN) of the Integrated Taxonomic Information System (ITIS) in the uploaded data file.
Reverse taxon match by AphiaID: Returns the Aphia record (scientific name, taxonomic status, etc.) based on the AphiaID of the World Register of Marine Species (WoRMS) in the uploaded data file.
Taxon match: Matches your taxon list with the World Register of Marine Species (WoRMS), Catalogue of Life (CoL), the Integrated Taxonomic Information System (ITIS), the Pan-European Species directories Infrastructure (PESI), the International Plant Names Index (IPNI), the Global Names Index (GNI), Index Fungorum (IF), and the Paleobiology Database (PaleoDB), based on the ScientificName in the uploaded data file.
​Tidal services:

Calculate tidal reduction: Calculates tidal heights in NAP (Normaal Amsterdams Peil), GLLWS (Gemiddeld Laag LaagWater bij Springtij), and TAW (Tweede Algemene Waterpassing) based on Latitude, Longitude and EventDate in the uploaded data file. The calculations are based on the M2 tidal reduction algorithm and the water levels measured by the monitoring network Flemish Banks.





Geographical services - Protected areas:

Flemish Ecological Network: Indicates if a given location is situated within the Flemish Ecological Network, based on Latitude and Longitude in the uploaded data file, and gives the type and name of the VEN-area. The Flemish Ecological Network (VEN) is a selection of valuable and sensitive natural areas in Flanders. The Flemish government gives priority to nature conservation and nature development in these areas.

Geographical services - Total biological valuation:

Marine Biological Valuation (total): Returns the total marine biological value of a location in the Belgian Continental Shelf, based on Latitude and Longitude in the uploaded data file and the Biological Valuation Map for the Belgian Continental Shelf (BWZee) produced in 2007.

Terrestrial Biological Valuation (v22): Returns the terrestrial biological value of a location in the Flemish Region, based on Latitude and Longitude in the uploaded data file and the Biological Valuation Map (version22). The Biological Valuation Map is a uniform field-driven survey of the land cover and vegetation in the Flemish Region.

Marineregions gazetteer services:

Get lat-long by mrgid: Returns the latitude and longitude of the centroid and the preferred gazetteer name of a Marine Regions ID (MRGID), based on the MRGID in the uploaded data file.

Get lat-long by name: Returns the latitude, longitude, matched name and the Marine Regions ID (MRGID) of a given gazetteer name in the uploaded data file.

Get gazetteer name by lat-long: Returns the Marine Regions place name and the Marine Regions ID (MRGID) of the bounding box (radius 3) based on Latitude and Longitude in the uploaded data file.

Get lat-long by accepted name: Returns the latitude, longitude, accepted name and the Marine Regions ID (MRGID) of a given gazetteer name in the uploaded data file.
