# python-api-challenge
Python API - What's the Weather Like?

## Part I - WeatherPy
Create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. Use a simple Python library and the [OpenWeatherMap](https://openweathermap.org/api) API to create a representative model of weather across world cities.

First build a series of scatter plots to showcase the following relationships:
- Temperature (F) vs. Latitude
- Humidity (%) vs. Latitude
- Cloudiness (%) vs. Latitude
- Wind Speed (mph) vs. Latitude

## Part II - VacationPy

Create a heat map that displays the humidity for every city from the part I

Next narrow down the DataFrame to find your ideal weather condition:
- A max temperature lower than 80 degrees but higher than 70.
- Wind speed less than 10 mph.
- Zero cloudiness.

Use the [Google Places API](https://developers.google.com/places/web-service/intro) to find the first hotel for each city located within 5000 meters of your coordinates.

Plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

## Solution(s)
All source files are located in this repository.  You will need to provide api keys to query the referenced datasets.

#### Part I - [WeatherPy](https://nbviewer.jupyter.org/github/kirpatrick/python-api-challenge/blob/master/WeatherPy/WeatherPy.ipynb)
*[data_output](https://github.com/kirpatrick/python-api-challenge/tree/master/WeatherPy/output_data)*

#### Part II - [VacationPy](https://nbviewer.jupyter.org/github/kirpatrick/python-api-challenge/blob/master/VacationPy/VacationPy.ipynb)

## Source
[SMU DS Boot Camp - Python API Challenge](https://smu.bootcampcontent.com/SMU-Coding-Bootcamp/SMU-DAL-DATA-PT-11-2019-U-C/tree/master/02-Homework/06-Python-APIs/Instructions)

## Tech Stack
- [Git 2.17.1](https://git-scm.com/downloads)
- [Python 3.7.4](https://www.anaconda.com/distribution/)
- [Google Places API](https://developers.google.com/places/web-service/intro)
- [OpenWeatherMap](https://openweathermap.org/api)
- [Jupyter nbviewer](https://nbviewer.jupyter.org/)
