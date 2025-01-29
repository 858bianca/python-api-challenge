# python-api

#Background

By using Python requests, APIs and JSON would aid in answering this question: "What is the weather like as we approach the equator?"

#Part 1: WeatherPy Notebook

In this part I created a Python script to visualize weather over 500 cities that are close to the equator. Before creating the script I uploaded my own Weather API from OpenWeatherMap API and used citipy Python library to help generate random coordinates of cities that are relatively close to the equator by longitude and latitude distance. This was than demonstrated using a series of scatter plots that showcased the following data: Latitude vs. Temperature, Latitude vs. Humidity, Latitude vs. Cloudiness, Latitude vs. Wind Speed. 
Next, I used a linear regression  to showcase the relationship between Northern Hemisphere and Southern Hemisphere for temperature, humidity, cloudiness, and wind speed. By doing so, it helped showcase some anaylysis such as, Northern Hemisphere has a negative correlation 
and Southern Hemisphere has a positive correlation when measuring Max temperature. For humidity and wind speed, both hempishperes showed a slight positive correlation, and no correlation was seen for cloudiness. 

#Part 2: VacationPy Notebook

In this section, the goal was to find ideal vacation spots based on the ideal weather conditions. To start off, I uploaded my Geoapify API key and used geoViews Python library. First, I created a map that showed every city from my DataFrame. Second, I narrowed down my DataFrame to show only cities with ideal weather conditions that meet my taste. Once those perameters were set, I created a new DataFrame to store the city, country, coordinates, and humidity, then used the Geoapify API to find hotels located within 10,000 meters of my coordinates. This was than displayed on a world map, when hover over the points will show a message for each city on the map. 
