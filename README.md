# Raspberry Pi Rice Cooker 2.0
Raspberry Pi-based web application to monitor the state of a rice cooker created by Tony DiCola. This version as a few updates of code and minor changes. It really can be used to monitor any device that provides date via simple LED lights. 

NOTE: I have learned so much from Tony DiCola's GitHub examples and videos. It appears he is no longer active here but the work he posted is still relavent and valuabel for beginers! 

<a href="http://imgur.com/m80danV"><img src="http://i.imgur.com/m80danVl.jpg"/></a><br/>
A photo of the rice cooker connected to the Raspberry Pi.

<a href="http://imgur.com/h9EjXbv"><img src="http://i.imgur.com/h9EjXbvl.png"/></a><br/>
The interface to the rice cooker is a simple web application hosted directly on the Raspberry Pi.

Created by Tony DiCola (tony@tonydicola.com)

## Requirements
To run the raspberry pi rice cooker code you must have the following setup with your raspberry pi:
* Python 3.10.x
* [Flask]((https://flask.palletsprojects.com/en/2.1.x/))
* [RPi.GPIO](https://pypi.python.org/pypi/RPi.GPIO)
* Photocell hooked up to pin 18, as per this [Adafruit tutorial](http://learn.adafruit.com/basic-resistor-sensor-reading-on-raspberry-pi/overview)

If all the requirements are satisfied, copy the files to a directory on your pi and run the server with the following command:
`sudo python server.py`

From a web browser access http://IP_of_your_raspberry_pi:5000/ to see the rice cooker status.

## Acknowledgements
The raspberry pi rice cooker is possible with help from:
* [Raspberry Pi](http://www.raspberrypi.org/)
* [Flask](http://flask.pocoo.org/)
* [RPi.GPIO](https://pypi.python.org/pypi/RPi.GPIO)
* [Adafruit Raspberry Pi Tutorials](http://learn.adafruit.com/category/raspberry-pi)
* [Bootstrap](http://getbootstrap.com/)
* [jQuery](http://jquery.com/)
* [flot](http://www.flotcharts.org/)
* [HTML5 Boilerplate](http://html5boilerplate.com/)

## License
This work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/deed.en_US).

<a rel="license" href="http://creativecommons.org/licenses/by/3.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/3.0/88x31.png" /></a>
