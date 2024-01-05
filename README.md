# python-api-challenge
This repository contains code that uses the Open Weather API to  find the weather conditions at hundreds of cities of random latitude and longitude. Linear regression analysis was performed using NumPy and SciPy to see if latitude and certain weather conditions are related. This code, plots, and analysis can be found in the WeatherPy ipynb file. Additionally, this repository contains code to parse through the city data of WeatherPy based on weather preferences, find hotels near the cities using the Geoapify API, and plot those cities on a map with the Geoviews library. This code can be found in the VacationPy ipynb file. The output file contains the plots for the linear regression analysis, as well as a CSV with the city and weather data produced from the WeatherPy code.
## API's used
https://openweathermap.org/api
https://www.geoapify.com/
## WeatherPy
The cities were randomly selected by randomly producing latitude and longitude numbers and performing API calls with those latitudes and longitudes. Any cities that were not found display "City not found". The plots and linear regression for each weather condition in relation to latitude can be found in the WeatherPy file, and the conclusions for each condition are listed below the plots.
## VacationPy
The cities gathered from the WeatherPy code were narrowed down by what I perceived as my ideal weather conditions.
For different weather conditions, just change the narrowing conditions for the city_data_df found near the top of the VacationPy file. 
