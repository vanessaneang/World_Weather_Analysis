# World_Weather_Analysis

## Overview
For the Client PlanMyTrip data was retrieved via World Weather API and Google Maps API in order to filter data to find optimal travel plans for users. The project was broken down into three different parts: (1) Extract Weather Data from OpenWeatherMap APIs, (2) Creating a Custom User Destination Map based on Weather Preferences, and (3) Creating a Travel Itinerary Map Based on Users Preferred Route.

## Extract Weather Data From OpenWeatherMap APIs

By generating a random set of 2,000 random latitude and longitudes utilizing np.random.uniform function. Theny using citipy module found the nearest city for each latitude and longitude combination. Retrieved the information to create weather DataFrame:

