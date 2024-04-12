# Python_API_Challenge
Python_API_Challenge

Part 1: WeatherPy

For this week's challenge, I was tasked to create scripts to visualise the weather of over 500 cities of varying distances from the equator in reference to the OpenWeatherMap API. The task was to create a series of scatter plots to display the following relationships:
1. Latitude vs. Temperature
2. Latitude vs. Humidity
3. Latitude vs. Cloudiness
4. Latitude vs. Wind Speed
After plotting the scatter plots, I was tasked to do so for both northern and southern hemispheres and then calculate the linear regression for each.

Part 2: VacationPy

As part of the challenge, I was taskted to create scripts to visualise how weather data can be used to plan futurue vacations using Geoapify API. The task was to create a map that displays a point for every city in the data set with the following steps: 
1. Create a map that displays a point for every city in the city_data_df DataFrame. The size of the point should be the humidity in each city.
2. Narrow down the city_data_df DataFrame to find your ideal weather condition. For example: A max temperature lower than 27 degrees but higher than 21, Wind speed less than 4.5 m/s, Zero cloudiness
3. Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity
4. For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates
5. Add the hotel name and the country as additional information in the hover message for each city on the map
