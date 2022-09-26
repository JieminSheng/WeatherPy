# WeatherPy Utilizing APIs: Planning with Python

## Overview of Project

### Background

The initial coordinates obtained are from a random number generator to create latitudes and longitudes across the planet. Then, a Python library is utilized to obtain the nearest cities to those randomly generated 2,000 coordinates with a list created to compile identified cities. Afterwards, an Application Programming Interface (API) from OpenWeather was utilized to obtain the recent weather conditions, including: maximum temperature, humidity, cloudiness, wind speed, and qualitative weather description, of the cities that had been added to the list. The user can then be prompted to enter their desired preferred maximum and preferred minimum temperature of the place they would like to travel, based on the maximum temperatures obtained earlier, to narrow down candidates for travel. A map is then presented of all possible locations including pop-up information boxes containing the hotel name, city, country, and current weather with the qualitative weather description and maximum temperature. An API from Google Maps is then used to find the nearest hotels. The user can then determine their desired country of travel, select for four cities to travel between and on what plan of stops, and mode of travel. A map is presented showing an itinerary between those cities and another map is presented with the information boxes with the same information as before but restricted to those four cities.

### Purpose

The purpose of this analysis is to determine four places to travel to, first with a random selection of locations to try for new experiences and then a parsing of those locations into a manageable itinerary with climate and other personal preferences of the user.
