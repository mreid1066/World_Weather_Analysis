# WeatherPy

## Overview of Project
For this project, we were tasked with continuing our use of the OpenWeatherMap API and GoogleMap APIs to improve upon the work we did for the PlanMyTrip app. Specifically we were first asked to include the current weather description to our DataFrame of cities we obtained through randomly generated latitudes and longitudes. This Information is included in the WeatherPy_Database.csv file. We were then tasked with updating our Customer Travel Destinations map with the new DataFrame that includes inputs for specific weather preferences. Finally, based on the weather prefernces, we were to include an itinerary using the Google Directions API to create a travel itinerary to at least 4 cities based on on those weather preferences.

*NOTE = When reading the WeatherPy_Database.csv file, Python Pandas automatically converted the country abbreviation code for Namibia from NA to NaN or a null vallue. We corrected this by identifying in which rows these errors occures and replaced them with the correct country abbreviation.
