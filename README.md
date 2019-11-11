# smart-sensor-revolution
We are creating a sensor that will be able to tell the humidity, temperature and time at any given location. Our sensor will be set up using 
RaspberryPi and Python code. We will then ouput the readings onto a spreadsheet. 

#Smart-Sensor-Revolution variables
1. temperature
2. humidity
3. time

#pip install w1thermsensor 
# sudo ap-git install git-core 
#install the AdafruitDHT11 library
#Install WiringPi 
This allows python to get the temperature from the thermometer that is set up in the Raspberry Pi hardware.
Then we import W1ThermSensor from w1thermsensor. This command also allows us to read the humidity as well.


# Interface
after installing and unpacking w1thermsensor we are then able to enable the interface.

#import time
After enabling the interface we are able to unpack the time library.

#While true
This will enable us to get the temperature, humidity and time every second forever until the loop is broken.

#temperature = sensor.get_temperature() and humidity= sensor.get_humidity()
This will allow us to retrieve the temperature from the sensor into the variable temperature.
Then this code will also allow us to retrieve the humidty and input it into the humidity variable.

Then we will print the results using the print function onto a spreadsheet.




