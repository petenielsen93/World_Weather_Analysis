# World_Weather_Analysis

## Purpose

The purpose of this project was to use the accumulation of our skills with Python, Pandas, Numpy, and calling APIs to create visualizations for our fictional app, PlanMyTrip. In the project, we first added a weather description to include on our vacation location description. To do that, we again called our OpenWeatherMap API to gather a list of 2000 random longitudes and latitudes, and created a DataFrame similar to the Dataframe used in the Module, but with the Current Description field added. (See the Weather Database folder.)

Next, we used input statements to filter our data for the user's preferences to drill down to certain cities. We also called the GoogleMaps API to find a hotel in the selected cities based on our parameters. We then created visualizations of our cities with the hotel data accessible through a layer of markers on our GoogleMap figure. (See the Vacation_Search folder.)

Finally, using Google Maps Directions API, we created a travel route between four Brazilian cities by grabbing their latitude and longitude through our Vacation DataFrame. Using these, we were able to plot a Directions map on our figure. We also created a map showing our hotels for the selected cities as well. (See the Vacation_Itinerary folder.)