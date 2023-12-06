# python-api-challenge

This folder contains two parts of our python-api challenge.

Part 1 - WeatherPy
--------------------------------------------------------
In the first part of the challenge, we use OpenWeatherMap API to get weather data for cities that are populated from the starter code.
We plotted some comparisons for a series of scatter plots about the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

We separated the data by hemisphere and discussed about the linear relationships for each series of scatter plots.

Part 2 - Vacation Py
--------------------------------------------------------

In the second part of the challenge, we use our weather data information to find ideal vacation spots. We are using the geoviews library and GeoApify API with Jupyter notebook.
In the first map, we have a plot of all city locations we pulled for the weather data analysis. The size of each city point is represented by the humidity level of the city. There is also a colour bar to help identify the humidity levels by colour as well.
We narrow down our most preferred cities for vacation based on:
- A max temperature lower than 27 degrees but higher than 21
- Wind speed less than 4.5 m/s
- Zero cloudiness

We created a second map to show the location of these preferred cities from a new dataframe.

