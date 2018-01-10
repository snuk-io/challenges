# Software Engineer / DevOps challenge

This is a challenge for the Front-end Developer at [snuk.io](http://snuk.io).

For the general information about the challenges please check the [README.md](/README.md).

## Temperature monitoring and control

You need to implement a web application that features following components:
- A graph showing temperature data
- Input of parameters that control random temperature data

Please deliver us a link to the application (Rafal, do we ask them to host it online? Or provide us something we need to run locally?)

### Temperature graph

The graph displays temperature data (X-axis is time, Y-axis is temperature in degrees centigrade)

The graph always displays the values from the last hour.

The values are to be taken from https://openweathermap.org/, please take values from Berlin.

An example graph:

![Image of services](/temperature-graph.png)

### Adding new data

Once the graph is loaded with the data from openweathermap, more data gets generated and added.
A random number between a minimum and maximum temperature gets added to the graph every certain amount of seconds.

The minimum and maximum temperature have a default value of respectively 10 and 30 degrees.
The default value for the time interval is 30 seconds.

### Changing the random numbers

The three values that control the addition of random numbers can be controlled on the user interface.
- minimum temperature
- maximum temperature
- time interval

These values can be changed using + and - buttons.

### Responsiveness

Make the webapp response so that it works on both desktop and mobile.

## Framework

Make your life easy by using a framework such as ReactJS.
