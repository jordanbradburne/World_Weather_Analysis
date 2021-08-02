# World_Weather_Analysis

## Project Overview
In this project, PlanMyTrip is a top travel technology company that is working on a travel app for customers. It uses weather data and data to recommend ideal hotels based on clients’ weather preferences of 500+ cities. This project will enhance the user interface and functionalities.

# Steps:
1. Retrieve weather data that includies the weather description for these cities
2. Create a customer travel destinations map
3. Create a travel itinerary map

## Resources
* Data Source: citipy, jupyter-gmaps, OpenWeatherMap API, Google Maps and Places API, Google Maps Directions API
* Software: Python 3.8.8, Anaconda Navigator 2.0.3, Conda 4.10.3, Jupyter Notebook 7.22.0

## Results
### Retrieve weather data
The app generates a set of 2,000 random latitudes and longitudes, retrieves the nearest city, and performs an API call with the OpenWeatherMap. It then retrieves the current weather description for each city.

<img width="591" alt="Screen Shot 2021-08-01 at 6 38 56 PM" src="https://user-images.githubusercontent.com/85847344/127793376-02bbf618-730d-41ad-8bd8-80664c0304cf.png">


### Create a customer travel destinations map
The app uses input statements to retrieve customer weather preferences, then uses those preferences to identify potential travel destinations and nearby hotels. These destinations are then shown on a marker layer map with pop-up markers.

<img width="835" alt="WeatherPy_Vacation_Map" src="https://user-images.githubusercontent.com/85847344/127793465-f287691c-7555-421d-924b-207a4f4b6c52.png">

### Create a travel itinerary map
* Using Google Maps Directions API the app generates a travel itinerary that shows a route between 4 cities selected by the user. 
<img width="835" alt="WeatherPy_Travel_Map" src="https://user-images.githubusercontent.com/85847344/127793706-ca383043-6254-414a-913f-7e8a79622426.png">

* Then, the app generates a marker layered map with a pop-up marker for each city on the itinerary.
<img width="848" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/85847344/127793707-6e69c61e-ad12-467f-a4f9-ac5c8f6c5bda.png">

