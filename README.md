# python-api-challenge

## Part 1: WeatherPy
In this deliverable, we create a Python script to visualize the weather of over 500 cities of varying distances from the equator. We use the citipy [Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across cities.

### Requirement 1: Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, we use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, we created a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

### Requirement 2: Linear Regression for Each Relationship
To fulfill the second requirement, we compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

Finally, we create a series of scatter plots. 
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

## Part 2: VacationPy
In this deliverable, we use our weather data skills to plan future vacations. Also, we use Jupyter notebooks, the geoViews Python library, and the Geoapify API.

1. Create a map that displays a point for every city in the `city_data_df` DataFrame. The size of the point should be the humidity in each city.
2. Narrow down the `city_data_df` DataFrame to find an ideal weather condition.
3. Create a new DataFrame called `hotel_df` to store the city, country, coordinates, and humidity.
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of the coordinates.
5. Add the hotel name and the country as additional information in the hover message for each city on the map.

## Code
This analysis was written in Python using a Jupyter Notebook.

- Repo: python-api-challenge
- Folder: WeatherPy
- Notebooks: WeatherPy.ipynb, VacationPy.ipynb
- Output: output_data folder