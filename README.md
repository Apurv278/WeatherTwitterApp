# WeatherTwitterApp
Waether App (Twitter Code Challenge)

Coding Exercise for Twitter
Please take no more than 3 hours to complete the following.
We would like you to create an Android app to display the weather:
● Use the provided starter code to get started.
● Use the API to fetch the current weather.
● Display the following current conditions:
○ Temperature in Celsius and Fahrenheit
○ Wind speed.
○ A cloud icon if the cloudiness percentage is greater than 50%.
● Provide a button, that when tapped, fetches the weather for the next 5 days, and displays
the standard deviation of the temperature, whose formula is provided below:
stddev = √ n−1
∑
n
i=1
(x −x)
i
2
n = number of data points
x = average/mean of the data
x each of the values of the data i =
∑ is the summation operator which is defined as the addition of all the elements of the
series. In this case it’s the addition of (x ) for each temperature in the series i − x
2
Because this is a brief exercise and not a full fledged app, the following is not required:
● The 5 days of weather, only the standard deviation of the 5 days is required.
● Persisting data across multiple app launches or refreshing the data while the app is
running.
● We know making a great-looking UI takes a lot longer than 3 hours. Your UI should be
functional and responsive, but is not expected to be attractive. You will be judged on the
quality of your code, not the style of your UI.
