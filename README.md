# World_Weather_Analysis
 
## Purpose
This anaylsis is meant to create a vacation map that allows potential customers to identify a preferred travel destination. Utlizing the Google API's we are able to give the user recommendations for hotels within a given distance of theri travel destination.

## Overview
In order to test our API tool we generated a list of 2,000 random longtitudes and latitudes. Using this dataset we were able to use citipy to find a list of the nearest cities. Using OpenWeather we were able to find the current weather for each unique city and provide the user a list of cities that matched their preferred min and max temperature for their trip. This resulted in a map that included city, country, current weather, description and hotel name.