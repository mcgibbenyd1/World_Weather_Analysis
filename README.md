# World_Weather_Analysis

## Project Overview
My trip is a top travel technology company that specializes in internet related services in the hotel and lodging industry. Jack is the head of analysis fot the user interface team. He's asked you to help him collect and present data for tcustomers via the search page, which they will the filter based on their preferred travel criteria in order to find their ideal hotel anywhere. To preform this task, you will be using a Jupyter Notebook and Citipy module to get cities for more than 500 random latitudes and logitudes then you will perform requests on the OpenWeather Map API and retrieve the JSON weather data from these cities. The weather dtat will be added to a Panda's dtatframe, where you will us Matplotlib to create a series of scatter plots to show the relationship between latitude and a variety of weather parameters for over 500 cities around the world. As part of the analysis, you will need to perform statistical calculations on the data using linear regression on the northern and southern hemispheres. This data will help your team predict the best time of year for people to plan their vacation based on certain weather criteria then map these cities using Jupyter G maps and the Google Places API. 

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software:Python 3.7.6, jupyter-notebook 6.0.3, Anaconda 4.13.0, Pandas 1.0.1, Matplotlib 3.1.3, OpenWeatherMap API, Google Directions API

## Challenge Overview
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Challenge Summary
2000 longitude and latitudes were randomly generated and the CitiPy module was used to evaluate the coordinates and return nearby cities with more than a 500 person population. The OpenWeatherMap API was then used to pull the weather for each of the cities in the list. A user input conditional was used to filter the cities based on a max and min temperature and then with Google Maps API ploted out on a world map. From there 4 cities were selected within the same country and a travel itinery generated. 

<p align="center">
World map displaying the cities fitting the temperature critera
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png" width="65%"/>
</p>

<p align="center">
4 cities selected within the same country to plan a vacation.
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png" width="65%"/>
</p>

<p align="center">
Travel itinerary with directions between the 4 selected cities. 
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png" width="65%"/>
</p>
