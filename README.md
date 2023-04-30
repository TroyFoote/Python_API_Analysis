# Python API Analysis
Module 6

## Project Description

## WeatherPy

create a Python script to visualise the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library, the OpenWeatherMap API, and your problem-solving skills to create a representative model of weather across cities.

### Instructions
This activity is broken down into two deliverables, WeatherPy and VacationPy.

## Part 1: WeatherPy

#### Requirement 1:
You will use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:


* Latitude vs. Temperature
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

#### Requirement 2: 

Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). You may find it helpful to define a function in order to create the linear regression plots.

Next, create a series of scatter plots. Be sure to include the linear regression line, the model's formula, and the r values as you can see in the following image
<br>

![Scatter Plot](Weatherpy/Resources/linear-regression-plot.png)
<br>

* Northern Hemisphere: Temperature (C) vs. Latitude
* Southern Hemisphere: Temperature (C) vs. Latitude
* Northern Hemisphere: Humidity (%) vs. Latitude
* Southern Hemisphere: Humidity (%) vs. Latitude
* Northern Hemisphere: Cloudiness (%) vs. Latitude
* Southern Hemisphere: Cloudiness (%) vs. Latitude
* Northern Hemisphere: Wind Speed (m/s) vs. Latitude
* Southern Hemisphere: Wind Speed (m/s) vs. Latitude

After each pair of plots, explain what the linear regression is modelling. Describe any relationships that you notice and any other findings you may uncover.


## Part 2: VacationPy

#### Requirement 1:
You wil use your weather data skills to plan future vacations. Also, you will use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Your main tasks will be to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualisations.

Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
<br>

![Humidity Map](Weatherpy/Resources/humidity_map.png)
<br>

* Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
* A max temperature lower than 27 degrees but higher than 21
* Wind speed less than 4.5 m/s
* Zero cloudiness

### Dependencies

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy stats
