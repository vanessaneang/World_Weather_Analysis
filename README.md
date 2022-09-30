# World_Weather_Analysis

## Overview
For the Client PlanMyTrip data was retrieved via World Weather API and Google Maps API in order to filter data to find optimal travel plans for users. The project was broken down into three different parts: (1) Extract Weather Data from OpenWeatherMap APIs, (2) Creating a Custom User Destination Map based on Weather Preferences, and (3) Creating a Travel Itinerary Map Based on Users Preferred Route.

## Extract Weather Data From OpenWeatherMap APIs

By generating a random set of 2,000 random latitude and longitudes utilizing np.random.uniform function. Theny using citipy module found the nearest city for each latitude and longitude combination. Retrieved the information to create weather DataFrame.

## Create User Based Destination Map 

Filtered Dataframe based on user preference for minimum and maximum temperature. From this information hotel names were retrieved and added to dataframe based on the cities that met the criteria. From here mark layer maps with pop-up markers for the cities with **hotel name, city, country, and current weather description with max temperature was created.**

## Creating a Travel Itinerary Map Based on Useres Preferred Route

With Google Maps API created a vacation itinerary map that shows directions for an itinerary that has four cities with the start and ending city being the same. In addition to this another map was created with markes that has the same pop-up markers that states: **hotel name, city, country, and current weather description.**
