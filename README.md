# World Weather Analysis
The primary purpose of this project is to experiment with Web API calls through Python.
- We made use of citypy APIs to generate several hundred random cities.
- We made use of Open Weather Map APIs to retrieve the weather information.
- We made use of gmaps and Google Maps APIs to retrieve nearby places and directions.

## Challenge
For this module's challenge, we wrote code to do the following:
1. For part 1, we generated a weather database [file](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Weather_Database/WeatherPy_Database.csv). The code can be found in the following Jupyter Notebook file: [Weather_Database.ipynb](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Weather_Database/Weather_Database.ipynb)
    - generated 2,000 random latitudes and longitudes.
    - called citypy APIs to convert the lats/lngs into city names.
    - called Open Weather Map APIs to retrieve weather
    - saved the weather file in CSV format
2. For part 2, we provided the ability to capture input and called Google APIs by prompting the user for criteria in a vacation search scenario. The code can be found here: [Vacation_Search.ipynb](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Vacation_Search/Vacation_Search.ipynb)
    - captured users maximum and minimum temperature
    - filtered the list of cities to temperature range
    - called Google APIs to find lodging in list of cities
    - saved output CSV file with city info along with nearest hotel
    - generated a map via gmaps with markers to showcase results
      ![Cities](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Vacation_Search/WeatherPy_vacation_map.png)
3. For part 3, we created a travel itinerary that includes directions and an overview of the destinations. The code can be found here: [Vacation Itinerary](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Vacation_Itinerary/Vacation_Itinerary.ipynb)
    - made use of gmaps to generate Google Maps with custom marker content
    - chose four cities and created directions map via gmaps
      ![Directions](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Vacation_Itinerary/WeatherPy_travel_map.png)
    - generated overview of trip with gmaps
      ![Overview](https://github.com/haldud/world-weather-analysis/blob/790aa97f117a15da919d4edf083e8fe88d869e80/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
