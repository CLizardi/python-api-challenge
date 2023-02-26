<h1>Python API Challenge with VacationPy</h1>

![craiyon_222543_show_the_world_and_all_of_its_continents__a_globe_is_fine__show_various_weather_metri](https://user-images.githubusercontent.com/52866379/221439576-286bf6ad-0a63-4bf3-969d-5b8f08635e10.png)

Python API Challenge
This is a project that I completed as part of a data analysis bootcamp course. The goal of the project was to analyze weather data for a set of cities around the world, and to see how various weather metrics (temperature, humidity, cloudiness, and wind speed) were affected by the latitude of the city. Additionally, I also used the Geoapify API to retrieve hotel information for each city.

The project consisted of two parts: retrieving the weather data using the OpenWeatherMap API, retrieving hotel information using the Geoapify API, and then analyzing the data using Python and various data analysis libraries (including Pandas, Matplotlib, and SciPy).

Getting the Data
To retrieve the weather data, I used the OpenWeatherMap API. I wrote a Python script that made API calls to the service to get current weather data for a set of cities around the world. I used the citypy library to generate a list of random cities, and then I used the API to retrieve the weather data for each city.

To retrieve hotel information for each city, I used the Geoapify API. I wrote a Python script that made API calls to the service to get hotel information based on the latitude and longitude of each city.

Analyzing the Data
Once I had the weather and hotel data, I used Python and various data analysis libraries to analyze the data and create visualizations. Specifically, I used Pandas to clean and manipulate the data, and Matplotlib and SciPy to create various charts and perform linear regression analysis.

Results
The results of the analysis can be found in the WeatherPy.ipynb and VacationPy.ipynb notebooks in this repository. The notebooks contain the code used to retrieve and analyze the data, as well as various charts and visualizations. In general, the analysis found that there were clear correlations between latitude and various weather metrics. For example, cities closer to the equator tended to have higher temperatures, while cities farther from the equator tended to have lower temperatures. Additionally, the VacationPy notebook displays a heatmap of the hotel locations based on the cities with the best weather conditions.

Overall, this project gave me a good opportunity to work with real-world data and practice my data analysis skills in Python, as well as work with APIs such as OpenWeatherMap and Geoapify.
