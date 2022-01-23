# World_Weather_Analysis

Uploading three challenges that I completed using APIs

## Weather Database
This folder contains a list of 715 cities I found by creating 2,000 random points of latitude-longitude. I used an API to download weather data from OpenWeatherMap.org, which I installed into a DataFrame. I saved these cities to a csv file called 'WeatherPy_Database.csv'

## Vacation Search
I wrote code to ask a user about the optimal temperatures they would like for their vacation, then I found a range of 323 cities that currently lie within this range (65-85 degrees on January 22). I created a DataFrame and added to it the name of a hotel within 5000 meters of the latitude-longitude of the city. Then I placed markers on all the cities that met the specifications of the request and created the map shown below.
![Vacation Map](https://github.com/JDittes/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png.png)

## Vacation Itinerary
I planned a road trip in my optimal zone using the APIs for Google Maps and Directions. I chose the country of South Africa and found four hotels there that would be my destinations on the trip. Then I mapped out a route, placing markers on the cities and hotels I would use.
![Road trip Itinerary](https://github.com/JDittes/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
