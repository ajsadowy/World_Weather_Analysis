# World_Weather_Analysis
## Layout

> Vacation_Itinerary (folder)  
> > Vacation_Itinerary.ipynb   
> > WeatherPy_Vacation_map.png.png   
> > WeatherPy_travel_map_makers.png   
---   
> Vacation_Search (folder)  
> > Vacation_Search.ipynb   
> > WeatherPy_vacation.csv   
> > WeatherPy_vacation_map.png   
---   
> Weather_Database (folder)   
> > WeatherPy_database.csv   
> > Weather_Database.ipynb    
---   
>.gitinore
---   
  
>README.md   
---   

   
## Purpose   
The purpose of this project was to practice using APIs (Application Programming Interfaces). The primary two source I used for this project were from OpenWeatherMaps.org and Google Maps. The objective of this series of protocols is to help generate a vacation itinerary built based on temperature preferences.   

First in the Weather_Database, I set up a protocol to generate random coordinates then proceed to find the nearest city it is located to and retrieve weather information from OpenWeatherMaps.org, then merge into a single dataframe (and convert to a CSV file).   

Utilizing the CSV file I set up a protocol in Vacation_Search to ask the user what range of temperature would they tolerate for their trip. (My input was 5 to 95.) The protocol will then filter the preferences and proceed to find a hotel in the filtered cities.   

Choosing 4 cities in Poland in Vacation_Itinerary, using Google’s API we set a directional itinerary map and hotel marker map for the trip.
