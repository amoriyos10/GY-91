# GY-91
This is contains the library and an example of how to use the chinese sensor GY-91.

Since I found pretty much imposible for the time being to find any good library that makes this two-in-one chip work at once, I created mine personally. 
This program is only a basic script that displays all data via serial. It is intended to be used as an example and not as a fully functional program. But hey! It works like a charm, and it is easy-to-use. Just plug and play!

Disclaimer: the code found in the libraries is NOT MINE. Thanks to Adafruit and rpicopter for creating all the libraries. The only thing that I made, was changing the I2C addresses, combine both codes and solve all the incompatibilities. As this chip has two different sensors.

# HOW-TO

 - Connections:

VIN --------- 5V

GND --------- GND

SCL --------- A5

SDA --------- A4

 - Dependecies:

All dependencies should be included in the folder here.

In case you find problems, here are the links for the original libraries:
       https://github.com/adafruit/Adafruit_BMP280_Library
       https://github.com/moderndevice/MotionPlug
       
 - Compatible devices:

I only tried with the Arduino UNO. Any device with a variant of the ATmega328 should also work fine.



----------------------------------------------------------------------------------------------------------------------------------------
 

Any future updates will be post here as the project continues.

You can leave any question to these e-mail: efren@boyarizo.es
