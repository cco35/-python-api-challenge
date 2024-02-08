This repository contains my submission for Assignment 6 in the Columbia Data Analytics Bootcamp. The assignment required us to validate a seemingly obvious statement using two different APIs.

I began by generating a set of random latitudes and longitudes and used the citipy package to determine the nearest city to each coordinate. Subsequently, I utilized a for loop and the OpenWeatherMap API to extract relevant weather data such as temperature, humidity, and cloudiness for each city. This information was then converted into a DataFrame. To ensure reproducibility and further analysis, I exported all this data into a CSV file.

Next, I generated scatter plots comparing some key weather variables and performed linear regression analysis on each to explore any potential relationships.

Using the CSV data I exported, I created a visualization displaying each city as a point on the map. After filtering the data as desired, I utilized the Geoapify API to locate the nearest hotel to each city within a designated radius.
