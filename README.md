# Proving weather trends according to distance from the equator

How do we prove that the temperature gets hotter the closer you get to the equator?

First, we randomly select over 500 latitude and longitude coordinates which we then map to cities across the globe.  This gives us a well distributed sampling of cities to examine temperature, humidity, cloudiness, and wind speed. Then, using the OpenWeatherMap API, we pulled the data for the various conditions for each city.  Lastly, we then graphed latitude vs temperature (as well as humidity, cloudiness, and wind speed) to examine the trends.  Looking at the data in scatterplot form, we see clearly that the closer to the equator, the hotter the temperature.  
