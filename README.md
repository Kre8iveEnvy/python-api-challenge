# python-api-challenge
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"   

## Model 6 Challenge is comprised of 2 parts

## Part 1: WeatherPY 
* Reference Jupyter Notebook [WeatherPy.ipynb](insertlink)for full code and text narrative.
* Using [OpenWeatherMap API](https://openweathermap.org/api) and [citipy Python library](https://pypi.org/project/citipy/) to create a representative model of weather across cities.
* For this part, you'll use the WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file. The starter code will guide you through the process of using your Python coding skills to develop a solution to address the required functionalities.
* Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed
* Requirement 2: Compute Linear Regression for Each Relationship
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude


## Part 2: VacationPY 
* Reference Jupyter Notebook [VacationPy.ipynb](insertlink)for full code and text narrative.
* In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
* Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
* Narrow down the city_data_df DataFrame to find your ideal weather condition.
* Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
* For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
* Add the hotel name and the country as additional information in the hover message for each city on the map. 
