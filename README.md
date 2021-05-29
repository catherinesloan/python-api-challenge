# python-api-challenge

## PART I - WeatherPy

### Task:
To utilise a Python library and the OpenWeatherMap API to create a representative model of weather across world cities.

### Output:
A [Python script](https://github.com/catherinesloan/python-api-challenge/blob/main/WeatherPy/WeatherPy.ipynb) that visualises the weather of 500+ cities across the world of varying distance from the equator. 
1. A random selection of 500+ unique cities based on latitude and longitude
2. A weather check on each of the cities using a series of successive API calls
3. A print log of each city as it's being processed with the city number and city name
4. [CSV](9https://github.com/catherinesloan/python-api-challenge/blob/main/WeatherPy/output_data/cities.csv) export of all retrieved data 
5. A series of scatter plots that showcases the following relationships:
   - Temperature (F) vs. Latitude
   - Humidity (%) vs. Latitude
   - Cloudiness (%) vs. Latitude
   - Wind Speed (mph) vs. Latitude
6. Linear regression on each relationship, seperated into Northern Hemisphere and Southern Hemisphere:
   - Temperature (F) vs. Latitude
   - Humidity (%) vs. Latitude
   - Cloudiness (%) vs. Latitude
   - Wind Speed (mph) vs. Latitude
 7. [PNG image](https://github.com/catherinesloan/python-api-challenge/tree/main/WeatherPy/images) export for each plot

## PART II - VacationPy

### Task:
Use jupyter-gmaps and the Google Places API to create a heat map that displays the humidity for every city from part I.

### Output:
A [Python script](https://github.com/catherinesloan/python-api-challenge/blob/main/WeatherPy/VacationPy.ipynb) which narrows down the DataFrame from part I to find my ideal weather conditions of
- Temperature 23 to 28 degrees celcius 
- Wind speed < 10
- Cloudiness < 1
1. Google Places API to find the first hotel for each city located within 5000 meters of locations with my ideal weather conditions.
2. A humidity [heatmap](https://github.com/catherinesloan/python-api-challenge/blob/main/WeatherPy/Screenshot%20of%20heat%20map.png) with plots of each of the hotels, including a pin containing;
   - Hotel Name
   - City
   - Country
