# World Weather Analysis

## Overview
For this analysis we will be gathering info for an app. This app is used by individuals wanting to plan a trip. To help the individual narrow down travel destinations based on temperature preference, the individual is asked what their preferred weather temperature is. For this analysis, random latitude and longitude locations for 2000 locations around the world were gathered. Weather data for these locations were collected through an API on the OpenWeatherMap. A DataFrame containing all weather data was created. Part of the data is displayed below.
![image](https://user-images.githubusercontent.com/26393180/152882644-bc73c015-1657-4e06-b5f0-e41953f73d1a.png)

After the individual specifies what temperature range is preferred for their upcoming trip, a subset dataset is created. This is used to provide travel recommendations.

## Analysis/Results
For this analysis we analyzed world weather data for an individual with a temperature preference between 75 degrees Fahrenheit and 90 degrees Fahrenheit.  A request was sent to retrieve info on hotels that were closest to the latitude and longitudes contained in the subset table. Pop Up markers were then added to gmaps. These pop up markers contain the Hotels name, City, Country and current description of the weather. 
![image](https://user-images.githubusercontent.com/26393180/152882713-2ae02015-dfbc-4298-8835-b931c2186e46.png)

From here, an itinerary was created based on the cities the individual would like to visit. For this analysis there were 4 cities in Venezuela that were selected: Puerto Rondon, Puerto Ayacucho, Puerto Carreno and Arauca. A travel route was created based on the selected cities. The below image shows the travel route for the four cities mentioned previously. 
![image](https://user-images.githubusercontent.com/26393180/152882746-13a70c07-c384-42fe-b5ed-fa29cf76b51c.png)

When the markers are clicked on, the individual can once again see the hotel name, city name, country, and current description of weather.
![image](https://user-images.githubusercontent.com/26393180/152882770-11d676bd-b4e5-421f-a528-bf4c9290c955.png)
