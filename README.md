# api-challenge
The goal of this challenge is to visualize the weather data for over 500 cities around the world. Then, using that data, be able to pick a vacation destination based on ideal weather conditions.

This challenge is broken down into two parts:

WeatherPy
Use citipy and OpenWeatherMap API to get weather data on 500+ cities
Create Scatter plots to visualize relationship between different weather conditions and city latitude
Compute linear regression models for each Relationship
Northern Hemisphere: Temperature vs. Latitude
Southern Hemisphere: Temperature vs. Latitude
Northern Hemisphere: Humidity vs. Latitude
Southern Hemisphere: Humidity vs. Latitude
Northern Hemisphere: Cloudiness vs. Latitude
Southern Hemisphere: Cloudiness vs. Latitude
Northern Hemisphere: Wind Speed vs. Latitude
Southern Hemisphere: Wind Speed vs. Latitude
VactionPy
Using geoViews and Geoapify API, along with weather data from WeatherPy, to plan a future vaction to a destination with ideal weather conditions
Create a map that displays a point for every city in city_data_df.
Size of each point should be humidity
Narrow down city_data_df based on ideal weather conditions
Find closest hotel to each city in narrowed down df
store hotel name in new df col
add hotel name and country as additional information in hover message on map
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
