# Python API Challenge - Analyzing Weather Data
![noaa-kcvlb727mn8-unsplash](https://github.com/CLizardi/python-api-challenge/assets/52866379/5adb32fd-8e9e-477c-b28c-d3091775f605)

# Introduction
In this project, I analyzed weather data from over 500 cities around the world using the OpenWeatherMap API. The goal was to explore the relationship between a city's latitude and various weather metrics such as temperature, humidity, cloudiness, and wind speed. Additionally, I used the Google Places API to find nearby hotels for cities with the best weather conditions.

# Project Overview
The project consisted of two parts: WeatherPy and VacationPy. In WeatherPy, I used Python and various data analysis libraries to retrieve weather data from the OpenWeatherMap API, store the data in a Pandas DataFrame, and create visualizations to analyze the data. In VacationPy, I used the Google Places API to find nearby hotels for cities with the best weather conditions and plotted the locations of the hotels on a heatmap.

# What I Did
In WeatherPy, I first generated a random list of over 500 cities using the citipy library. Then, I used the OpenWeatherMap API to retrieve weather data for each city and stored the data in a Pandas DataFrame. I cleaned and manipulated the data using Pandas, and created visualizations using Matplotlib and SciPy. The visualizations included scatter plots, regression lines, and heatmaps. Finally, I analyzed the data to find correlations between a city's latitude and various weather metrics.

In VacationPy, I used the cleaned data from WeatherPy to find cities with the best weather conditions. I used the Google Places API to find nearby hotels for each of these cities and stored the hotel data in a separate DataFrame. I then used gmaps and the Google Maps API to plot the locations of the hotels on a heatmap.

# Tools Used
* Python
* Pandas
* Matplotlib
* SciPy
* gmaps
* OpenWeatherMap API
* Google Places API
* Google Maps API

# What I Learned
Through this project, I learned how to work with APIs to retrieve and store data, and how to use various data analysis libraries in Python. I also learned how to create visualizations to analyze and interpret data. Additionally, I gained experience in data cleaning and manipulation using Pandas.

# Conclusion
The results of the analysis showed clear correlations between latitude and various weather metrics. Cities closer to the equator tended to have higher temperatures and humidity, while cities farther from the equator tended to have lower temperatures and higher wind speeds. The heatmap in VacationPy showed the locations of nearby hotels in cities with the best weather conditions, providing useful information for travelers. Overall, this project was a great learning experience and provided valuable insights into data analysis and visualization.
