# api-challenge

## Description
This project pulls, plots, & analyzes weather data from a randomly generated group of cities.

### WeatherPy*
- Creates a random list of ~500-600 cities, pulls weather info from the OpenWeatherMap API, & analyzes this data
- [**output_data**](output_data) includes the resulting csv file that we create in WeatherPy. [**req2**](req2) includes four scatterplots, showcasing these cities' latitudes vs. various weather variables: temperature (plotted in Celsius), humidity, cloudiness, and wind speed. The rest of the png files in [**req2**](req2) are split by northern/southern hemisphere and include a regression line. See the Jupyter Notebook file for more discussion on the regression lines.

### VacationPy
- Plots these cities on a map
- Cuts the data down to the cities that match our weather variable preferences
- Finds & saves the closest hotel for each city using the Geoapify API

## Sources:
* Starter code provided by the bootcamp (along with code from previous class activities)
* Geoapify docs

<!-- 
## Misc: 
* Had many issues with importing the hvplot.pandas module correctly in VacationPy - had to uninstall/reinstall/reconfigure a bunch of different modules w/ the help of ChatGPT - it apparently needed an earlier version of NumPy
*  -->
