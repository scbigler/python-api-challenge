# python-api-challenge

# FYI to graders - there are no regression lines shown because of an error being thrown when I try to plot a line. I get the regression equation, but the by adding the line of code to plot the line I get the error.  Even the instructor had no idea after looking at it, and I spent hours and hours researching online.  I gave up and decided to submit as-is.  I mention this only so you do not have to mention it in your notes.  Grade as you see fit.


In this challenge, current maximum daily temperature, humidity, cloudiness, and wind speed were pulled through an api from http://api.openweathermap.org in order to create scatterplot charts and anaysis to test the idea that higher maximum temperatures occur closer to the equator than they do farther from it. To accomplish this, a list of 1500 randomly selected cities were selected around the world and the cities on that list were fed into a get request for the weather information via an api call.  The goal was to return at least 500 cities, since it is assumed that not all 1500 random cities will have availible weather information on openweathermap.com.  

Once the weather information was returned, analysis could be done on the data that included scatterplots and linear regression when appropriate. The data pull was done on 2022/09/19.  A png file was created of each scatterplot and are located in the WeatherPy folder.  A short analysis is located in the WeatherPy.ipynb file, directly under each chart. 
