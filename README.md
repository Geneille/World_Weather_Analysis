# World_Weather_Analysis

## Overview & Objectives

This project aims to plan a trip for a vacation based on a specific temperature criteria between 75 and 90 degress Fahrenheit. With no specific destination in mind, and hence no lodging location, certain steps were undertaken to provide a complete vacation iternary. To fulfill this goal, the following objectives were completed:
1. Retrieve weather data by generating a set of random latitudes and longitudes
2. Create a travel destinations map based on customer input temperature preferences
3. Create a travel itinerary map

## Analysis Overview

 Calling on numpy random function in Jupyter Notebook, a set of 2,000 random latitudes and longitudes was first generated and the nearest city to these geographical location was retrieved. An API call with the OpenWeatherMap was then made to collect the city weather data, including the current weather description (at the time the call made). The Figure below portrays the data collected for some cities. The information was stored in a DataFrame and exported (WeatherPy_Database.csv) for further analysis.

Using the weather data collected, a set of cities and nearby hotels was selected as potential travel destinations based on preferred input temperature in Jupyter Notebook. These destinations were then illustrated on a map with pop-up markers.

Finally, the Google Directions API was used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. A marker layer map with a pop-up marker for each city on the itinerary was also created.

## Results

Table 1 below provides an illustration of the data collected for a few cities.



Table 2 below illustrates the filtered cities, a count of 185, with nearby hotels.

The map is portrayed in Figure 1.

Figure 2 below shows the proposed roadtrip for a vactaion in Braxil, visiting major cities on the coast

REWIND