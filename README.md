# Analyzing the impact of area-level deprivation and demographic trends on the restaurant industry in London
## 1. Introduction
### 1.1 Background
London is the capital of England and the United Kingdom and one of the largest and most important cities in the world. It has a diverse range of people and cultures that currently make the city one of the most populate cities in the world with 9,787,426 inhabitants registered at the 2011 census.[1]
With such a large number of inhabitants, the deprivation levels and population density can vary immensely between the 32 local authorities, also known as the London boroughs. 
### 1.2 Business problem
London is not only known for its population size and diversity but also for the restaurant industry which plays an important role in the city's economy. 
For this reason, in this project I will be comparing and analysing the different deprivation levels and population demographics across London's boroughs and their impact on the restaurant industry, specifically, what types of restaurants and their costs can be found in different boroughs.
### 1.3 Interest
The findings of this research can help potential/existing restaurateurs looking to open a new restaurant or Chain Restaurant stakeholders, by identifying new suitable locations for their business based on various characteristics such as:
- food cost
- number of competing restaurants in the area
- population density 
- area-level deprivation 

## 2. Data
To achieve the goals set out in this project, various types of data will be explored and analysed. This includes real-time location data using the Foursquare API[2], geospatial data using Python Geocoder library[3] and GADM (Database of Global Administrative Areas) data, Indices of Deprivation data[4] and London Borough Profiles data using the online London Datastore[5].
### 2.1 Foursquare API
Foursquare is a social networking service that provides independent location data. The purpose of the platform is to provide users with information about businesses and attractions around them using real-time location data.[6]
This API will be instrumental in identifying detailed information about restaurants across London.
### 2.2 Python Geocoder library
Geocoder is a simple and consistent geocoding library written in Python. I helps developers to locate the coordinates of addreses, cities, countries and landmarks across the globe.
The Geocoder will help get the coordinates for every London borough. 
### 2.3 GADM (Database of Global Administrative Areas) data
GADM is a high-resolution database of country administrative areas, with a goal of "all countries, at all levels, at any time period. The database includes shapefiles that are used in Geographic Information System (GIS) applications. 
### 2.4 Indices of Deprivation data and London Borough Profiles data
The Index of Multiple Deprivation 2007 combines a number of indicators, chosen to cover a range of economic, social and housing issues, into a single deprivation score for each small area in England. This allows each area to be ranked relative to one another according to their level of deprivation.[4]  
Index of deprivation will be used to assign a deprivation score to each London borough.

The London Borough Profiles help paint a general picture of an area by presenting a range of headline indicator data in both spreadsheet and map form to help show statistics covering demographic, economic, social and environmental datasets for each borough, alongside relevant comparator areas. This information will be used to understand each borough’s demographic trends. 

[1] ["2011 Census – Built-up areas"](http://www.nomisweb.co.uk/articles/747.aspx) ONS. Retrieved 08 January 2020  
[2] [“Foursquare API”](https://developer.foursquare.com/)  
[3] [“Python Geocoder”](https://geocoder.readthedocs.io/)  
[4] [“Indices of Multiple Deprivation, Borough”](https://data.london.gov.uk/dataset/indices-multiple-deprivation-borough)  
[5] [“London Borough Profiles data”](https://data.london.gov.uk/dataset/london-borough-profiles)  
[6] [“Foursquare”](https://foursquare.com/)  
