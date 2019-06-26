# Weather-Map-API
For this project I used Python requests, APIs, and JSON traversals to explore the relationship between climate aspects and latitude. This project was created using Pandas and Matplotlib in a Jupyter Notebook. 

I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized the [CityPi Python library](https://pypi.python.org/pypi/citipy) and the [OpenWeatherMap API](https://openweathermap.org/api) to create a representative model of weather across world cities.

My objective was to build a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

My final notebook:

* Randomly selected 500 unique (non-repeat) cities based on latitude and longitude.
* Performed a weather check on each of the cities using a series of successive API calls.
* Included a print log of each city as it was being processed with the city number and city name.
* Saved both a CSV of all data retrieved and png images for each scatter plot. Each plot featured Plot Titles (with date of analysis) and Axes Labels

![temp](https://raw.githubusercontent.com/robeaseab/Weather-Map-API/master/output_data/Weather_1_scatter_lat_v_temp.png)
![humidity](https://raw.githubusercontent.com/robeaseab/Weather-Map-API/master/output_data/Weather_2_scatter_lat_v_humidity.png)
![cloudiness](https://raw.githubusercontent.com/robeaseab/Weather-Map-API/master/output_data/Weather_3_scatter_lat_v_cloudiness.png)
![wind_speed](https://raw.githubusercontent.com/robeaseab/Weather-Map-API/master/output_data/Weather_4_scatter_lat_v_wind_speed.png)
