# world_weather_analysis

## Project Objective: 
Add to PlanMyTrip app that provides users with weather data, hotel information, etc to help them plan their trips.Specifically, we added current weather description data and allowed user input to filter desired min and max temp based on the user's weather preferences. 

## Methodology: 
1. First we generated a random list of 2,000 coordinates, retrieved the nearest city and did an API call to extract weather data from OpenWeatherMap. All this data was exported into 'weatherpy_database.csv'. 
2. Using the weatherpy_dabase csv file, the user was able to input a desired min and max temp to filter the csv file. We did an API call from Geoapify Places to extract the nearest hotels to the preferred cities. 
3. Lastly, we wanted to create a travel itinerary for 4 random cities. 4 cities in Italy were chosen at random and a map was generated using GeoViews. 

## Results: 
Based on user input, we created a map using GeoViews to display the filtered cities: 
<img width="673" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/113721712/213933126-155c5763-44d7-4da5-97b6-5fe544afe692.png">

For the 3rd deliverable, 4 cities were chosen at random to create a travel itinerary: 
<img width="255" alt="Map_4_cities" src="https://user-images.githubusercontent.com/113721712/213933342-42d93fd8-d4d8-48a4-a0e1-f2b7dda19e17.png">


## Currently stuck on how to create a visual that includes a route between all 4 cities. 
