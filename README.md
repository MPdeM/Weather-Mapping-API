# python-api-challenge
Python API weather mapping uses 
third party APIs with Python. 

Data is scratched from OpenWeatherMap (https://openweathermap.org/api). The JSON  are loaded fro the API responses into Pandas DataFrame.  

The notebook randomly select at least 500 cities are generated with varying distance from the ecuator. The weather information is fetched by ussing succesive API calls.  Then several scater plots are geneated:
    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude

Finally , CSV file of all data retrieved and png images for each scatter plot.data are saved in the /output_data and /output_plots folders. 
