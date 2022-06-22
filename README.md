# World_Weather_Analysis_
Project Overview
This project is the based on analysis, visualization, and statistical skills for retrieving and analyzing weather data for a hypothetical travel company, PlanMyTrip.

Summary
In the projects, API's were used to generated 2000 random Latitude and Longitude coordinate pairs across the world. Closest city to each of those coordinate pairs were identified. Then retrieved, collected, and cleaned weather data from each city coordinate pair and used weather data to help prospective vacationers find a city and hotel with their weather preferences. 
Weather description added to the weather data. Four cities were chosen to create a travel itinerary. Using Google Maps Directions API, a travel route was created between those four cities and marker layer added to the map.

Create Weather Database
•	Generated 2000 pair of latitudes and longitudes.
•	Used citipy API, to get the following information for each city: latitudes & longitudes, max temperature, humidity, cloudiness, wind speed, weather description and country.

Vacation Search
•	Used google maps API to locate nearby hotels, created Dataframe for Destination information and the name of the hotels. Then export DataFrame as csv file.
•	Generated map with marker and info box for the vacation search.

Vacation Itinerary
•	Four cities were selected to create the final travel itinerary. The cities selected are Pacific Grove, Flagsstaff, Wilmington and Freeport. The cities are in USA.
•	Used google maps Direction API to create the travel route driving between the four cities 
•	Generated a map with marker and info box for the four cities.

