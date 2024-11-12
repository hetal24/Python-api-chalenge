# Python-api-chalenge

# WeatherPy
- WeatherPy is a Python-based data analysis project that explores the relationship between different weather conditions and latitude across various cities. Using the OpenWeatherMap API, we retrieve real-time weather data. The project analyzes how temperature, humidity, cloudiness, and wind speed vary across different latitudes.

- To get the weather API key, use this link: OpenWeatherMap API.
- Install the citipy library using the command: pip install citipy.

1 Create Plots to Showcase the Relationship Between Weather Variables and Latitude:
   
    -Latitude vs. Temperature
    
    -Latitude vs. Humidity
    
    -Latitude vs. Cloudiness
    
    -Latitude vs. Wind Speed

2  Compute Linear Regression for Each Relationship:
    
    -Northern Hemisphere: Temperature vs. Latitude
    
    -Southern Hemisphere: Temperature vs. Latitude
    
    -Northern Hemisphere: Humidity vs. Latitude
    
    -Southern Hemisphere: Humidity vs. Latitude
    
    -Northern Hemisphere: Cloudiness vs. Latitude
    
    -Southern Hemisphere: Cloudiness vs. Latitude
    
    -Northern Hemisphere: Wind Speed vs. Latitude
    
    -Southern Hemisphere: Wind Speed vs. Latitude




# VacationPy
- VacationPy is a project that helps users plan vacations based on weather data. Using the Geoapify API and the geoViews library, the project displays travel destinations based on preferred weather conditions, including temperature, humidity, cloudiness, and wind speed. It filters cities that meet these ideal conditions and finds nearby hotels within a 10,000-meter range. The hotel name and country are displayed as additional information in the hover message for each city on the map.

- To get the Geoapify API key, use this link: Geoapify API.
- To install the necessary packages, run the following command: conda install -c pyviz hvplot geoviews -y.

1 Create a map that displays a point for every city in the city_data_df DataFrame.

2 Narrow down the city_data_df DataFrame to find your ideal weather condition.
    
    -A max temperature lower than 27 degrees but higher than 21
    
    -Wind speed less than 4.5 m/s
    
    -Zero cloudiness

3 Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

4 For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

5 Add the hotel name and the country as additional information in the hover message for each city.
