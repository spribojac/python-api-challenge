<picture>
 <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
 <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
</picture>

# API Challenge
## Module 6 API Challenge for University of Birmingham Data Analytics Bootcamp
### Description
-------------------------------------------------------------------------------------------------------------------------------------------------
### WeatherPy Challenge
------------------------------------------------------------------------------------------------------------------------------------------------
Create a Python script to visualize the weather of over 500 cities of varying distances from the equator. Use the citipy Python libraryLinks to an external site, the OpenWeatherMap APILinks to an external site to create a representative model of weather across cities.

Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
Create a series of scatter plots to showcase the following relationships:
- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
Compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) and create a series of scatter plots.
Create the following plots:
- Northern Hemisphere: Temperature vs. Latitude
- Southern Hemisphere: Temperature vs. Latitude
- Northern Hemisphere: Humidity vs. Latitude
- Southern Hemisphere: Humidity vs. Latitude
- Northern Hemisphere: Cloudiness vs. Latitude
- Southern Hemisphere: Cloudiness vs. Latitude
- Northern Hemisphere: Wind Speed vs. Latitude
- Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, explain what the linear regression is modeling. Describe any relationships that you notice and any other findings you may uncover.

------------------------------------------------------------------------------------------------------------------------------------------------
### Part 2: VacationPy
------------------------------------------------------------------------------------------------------------------------------------------------
- Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
- Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:
   - A max temperature lower than 27 degrees but higher than 21
   - Wind speed less than 4.5 m/s
   - Zero cloudiness

- Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
- For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
- Add the hotel name and the country as additional information in the hover message for each city on the map.

### Credits
-------------------------------------------------------------------------------------------------------------------------------------------------
Thank you to the bootcamp study groups. I built my logic around the exercises shared in class. I also used Geoapify and OpenWeather API.



