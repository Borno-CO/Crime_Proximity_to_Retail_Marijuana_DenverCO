# Crime_Proximity_to_Retail_Marijuana_DenverCO
## Denver University Data Analytics Boot Camp - Project 1
## Students: David Born, Sam Ewing

## Project Summary
We were curious whether legalized recreational maijuana sales were having an affect on crime in Denver. When there was public discussion prior to legalizing recreational marijuana, one of the expressed concerns was that legalized sales would promote an increase in crime. We found a very robust dataset of Denver crime data. We also found data for retail stores that were licensed to sell marijuana. The stores were authorized to start selling recreational marijuana in January 2014.

This project examined the City of Denver's crime data in relation to the local recreational cannabis industry. In particular, we compiled the city's crime rates  broken into police districts as well as the frequency of crimes in proximity to dispensaries (within a given radius). 

We originally set out to look at crime before and after January 2014 in order to compare crime activity before and after legalization. However, we discovered the available crime data was limited in terms of historical scope and there was no crime data prior to January 2014. So, we decided to alter our inquiry and look at crime patterns since the legalization of recreational marijuana by date of dispensary license: Pre-2014 licensed stores and Post-2014 stores.

Given the available crime data, we aimed to answer the following questions:

1) Has per capita crime grown in Denver, since the legalization of marijuana?

2) Is there a correlation between the number of marijuana stores by Denver Police District and crime?

3) Have crimes increased in neighborhoods around marijuana stores that were newly licensed in the years following legalization?


## To Access Our Project Findings
The analysis of our findings is provided in the markdown at the end of the Jupyter Notebook entitled: *Group-Project-1-Master.ipynb*


## Data Sources
### Denver Crime Data 
Kaggle: https://www.kaggle.com/paultimothymooney/denver-crime-data 

### Population Data (used 2010 US Census as a basis for projected estimates)
Live Population: http://livepopulationof.com/population-of-denver/

### Marijuana Business Licenses
Denver Open Data Catalog>Marijuana Active Business Licenses: https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-marijuana-active-business-licenses

### Denver Police Districts and Shapefile
Denver Open Data Catalog>Police Districts: https://www.denvergov.org/opendata/dataset/city-and-county-of-denver-police-districts

### Google Geocoding for Store Lat-Lngs
Google Geocoding API: https://developers.google.com/maps/documentation/geocoding/start


## Technologies and Special Libraries
Python, Pandas, Numpy, Matplotlib, Geopandas, Folium, Shapely, Haversine
