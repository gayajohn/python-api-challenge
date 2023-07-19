# Module 6 Assignment: APIs in Python

-----------------
Table of Contents
-----------------

WeatherPy Folder which contains

  - WeatherPy.ipynb file. This is the main script.
 
  - output_data folder with contains the .csv files used in the script

       - cities.csv that was generated with the script above, containing the information on the sample of cities generated in the VacationPy script
       - Fig1.png, a scatter plot of the city latitude vs. maximum temperature of the sample
       - Fig2.png, a scatter plot of the city latitude vs. humidity of the sample
       - Fig3.png, a scatter plot of the city latitude vs. cloudiness of the sample
       - Fig4.png, a scatter plot of the city latitude vs. windspeed of the sample


VacationPy Folder which contains

  - VacationPy.ipynb file. This is the main script.
 
  - output_data folder with contains the .csv files used in the script

       - cities.csv folder that was generated in the previous script

    
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-------------------
Challenge Objective
-------------------

In this project, a sample of cities was created based on a randomly generated longitudes and latitudes. The objective of the first challenge, WeatherPy, is to analyse the relationship between latitude and various weather factors such as wind speed, temperature, humidity and cloudiness. The objective of the second challenge, Vacation Py, is to narrow down the sample of cities to ones that meet some "ideal weather" conditions, and find hotels in these cities. 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-----------
API's used
-----------

- Geoapify: Geocoding to find latitude and longitudes and locating points of interest on a map.

  https://www.geoapify.com/

- CitiPy: Looking up cities with geocoordinates

  https://github.com/wingchen/citipy

- OpenWeather API: Get weather information on given cities

  https://openweathermap.org/api

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

----------
References
----------

Here are the references used in my code:

1) To learn how how to use Pandas .copy() function:

   https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.copy.html

   https://www.w3schools.com/python/pandas/ref_df_copy.asp

   Code referenced:

   hotel_df = ideal_weather_cities.copy()
   

2) To learn how to call today's date:

   https://www.programiz.com/python-programming/datetime/current-datetime
   
   Code referenced:

   #calling today's data

   from datetime import date

   today = date.today()

   print("Today's date:", today)


   

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
