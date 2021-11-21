# World_Weather_Analysis

## Purpose

The founder of the PlanMyTrip app wants to enhance the app's capabilities. Beta testers recommended including weather descriptions in the weather data and adding the ability to filter the data for their weather preferences. With this feature, beta testers will be able to identify potential travel destinations and nearby hotels. In this World Weather Analysis, a beta tester has chosen four cities and created a travel itinerary with a travel route between the them. 

## Weather Data

By performing an API call with OpenWeatherMap, the following information was retrieved from a random list of latitudes and longitudes:

- City, 
- Country
- Latitude and longitude
- Maximum temperature
- Humidity
- Cloudiness
- Wind speed
- Current description (examples include light rain, clear sky, scattered clouds, etc.)

This is a snapshot of the Dataframe.
![city_data_head](https://user-images.githubusercontent.com/90656004/142777115-03a145d7-122b-4668-a376-e39f2a9334c7.PNG)


## Vacation Search

Using input statements, user weather preferences were used to identify potential travel destinations along with nearby hotels. The following image shows all of the customer's travel destinations based on their preferences. 

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/90656004/142777189-0f4aafa7-bcd4-4450-bbf3-ccb4591ca9c6.PNG)


## Vacation Itinerary

The customer chose the following cities for their vacation: 
- Start and End Destination: Terrasini in Italy
- Stop 1: Haurterive in France
- Stop 2: Liverpool in Great Britain
- Stop 3: Skibbereen in Ireland. 

Using the Google Directions API, the travel itinerary shows the route between the four cities chosen from the customer's potential travel destinations.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/90656004/142777203-818a9058-4bae-4081-ac9d-35075fa1b591.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/90656004/142777208-3fd9a8a0-39f5-45af-8eb5-7dd0aad2bfb3.png)

![WeatherPy_travel_map_markers_locations](https://user-images.githubusercontent.com/90656004/142777212-b1b48d9c-9f52-4ce0-bf0e-1a09f95bf9c2.png)
