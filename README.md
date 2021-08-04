# Weather and Map API
## Overview
This project added weather infomation to each city. And then, people can restrcit the range of temperature to find suitable cities they want to go. When people selected some cities with comfortable temperature, they can also find the navigation between these cities.
## Resources
*Weather Database* : [WeatherPy_Database.csv](https://github.com/cffhr99/Module6-Challenge/blob/main/WeatherPy_Database.csv), [WeatherPy_Database.ipynb](https://github.com/cffhr99/Module6-Challenge/blob/main/WeatherPy_Database.ipynb)  
*Vacation Search*: [WeatherPy_vacation.csv](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Search/WeatherPy_vacation.csv), [Vacation_Search.ipynb](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Search/Vacation_Search.ipynb), [WeatherPy_vacation_map.PNG](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)  
*Vacation Itinerary*: [Vacation_Itinerary.ipynb](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Itinerary/Vacation_Itinerary.ipynb), [WeatherPy_travel_map.PNG](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG), [WeatherPy_travel_map_markers.PNG](https://github.com/cffhr99/Module6-Challenge/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
## Weather Database
A random 2000 pairs of latitude and longitude were generated and then *citipy* was used to find nearest city of each pair of latitude and longitude. After removing missing data, *OpenWeather API* was used to provide the weather information, which was listed below, to each city:
  - City
  - Country
  - Latitude
  - Longitude
  - Maximum Temperature
  - Humidity	
  - Cloudiness	
  - Wind Speed	
  - Current Description
## Vacation Search

## Vacation Itinerary
