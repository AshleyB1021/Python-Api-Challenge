# WeatherPy and VacationPy

## Overview

In this assignment, I created a Python scripts to visualize the weather of over 500 cities of varying distances from the equator using the citipy Python library, the OpenWeatherMap API, and your problem-solving skills. I also use Jupyter notebooks, the geoViews Python library, and the Geoapify API to plan future vacations based on weather data.

## Part 1: WeatherPy

### Requirements
Create plots to showcase the relationship between weather variables and latitude:

* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed
* Compute linear regression for each relationship and separate the plots into Northern Hemisphere and 
  Southern Hemisphere.

### Instructions

* Use the provided WeatherPy.ipynb Jupyter notebook.
* Generate random geographic coordinates and find the nearest city to each latitude and longitude combination.
* Retrieve weather data from the OpenWeatherMap API for the cities list.
* Create scatter plots and include the linear regression line, model's formula, and r values.
* Explain what the linear regression is modeling and describe any relationships you notice.

  ## Part 2: VacationPy

 ### Requirements

* Create a map displaying a point for every city in the city_data_df DataFrame with the size of the point as the humidity in each city.
* Narrow down the city_data_df DataFrame to find your ideal weather condition (e.g., max temperature lower than 27 degrees but higher than 21, wind speed less than 4.5 m/s, zero cloudiness).
* Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
* Use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates for each city.
* Add the hotel name and country as additional information in the hover message for each city on the map.

### Instructions
* Use the provided VacationPy.ipynb starter code.
* Import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1.
* Create map visualizations using the Geoapify API and the geoViews Python library.
* Follow the specified criteria to find your ideal weather condition and locate hotels near the cities.
* Add hotel names and countries as additional information on the map.


