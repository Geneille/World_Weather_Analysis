# World_Weather_Analysis

## Overview & Objectives

This project aims to plan a trip for a vacation based on a specific temperature criteria between 75 and 90 degress Fahrenheit. With no specific destination in mind, and hence no lodging location, certain steps were undertaken to provide a complete vacation iternary. To fulfill this goal, the following objectives were completed:
1. Retrieve weather data by generating a set of random latitudes and longitudes
2. Create a travel destinations map based on customer input temperature preferences
3. Create a travel itinerary map

## Analysis Overview

 Calling on numpy random function in Jupyter Notebook, a set of 2,000 random latitudes and longitudes was first generated and the nearest city to these geographical location was retrieved. An API call with the OpenWeatherMap was then made to collect the city weather data, including the current weather description (at the time the call made). The information was stored in a DataFrame and exported (WeatherPy_Database.csv) for further analysis.

Using the weather data collected, a set of cities and nearby hotels was selected as potential travel destinations based on preferred input temperature in Jupyter Notebook. These destinations were then illustrated on a map with pop-up markers.

Finally, the Google Directions API was used to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. A marker layer map with a pop-up marker for each city on the itinerary was also created.

## Results

Table 1 below provides an illustration of the data collected for a few cities.

<img width="690" alt="TABLE 1" src="https://user-images.githubusercontent.com/92636438/145733061-a7ee6167-de7f-44b6-88f7-a034db012ef8.png">


Table 2 below illustrates the filtered cities, a count of 185, with nearby hotels.

<img width="687" alt="TB 2" src="https://user-images.githubusercontent.com/92636438/145733100-9dbb496c-d8d0-4e90-b0fa-ffbf6a6c7e1a.png">


The map is portrayed in Figure 1 below.


Figure 1
<img width="739" alt="fig 1" src="https://user-images.githubusercontent.com/92636438/145733182-9e991c29-5669-4e20-b176-369c2dea8c08.png">


Figure 2 below shows the proposed roadtrip for a vactaion in Braxil, visiting major cities on the coast.

Figure 2
<img width="615" alt="fig 2" src="https://user-images.githubusercontent.com/92636438/145733213-27292af4-ef6d-46c7-a768-175fe9254ed1.png">

