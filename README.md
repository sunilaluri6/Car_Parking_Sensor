# Car_Parking_Sensor
ARM mbed LPC1768 based Car Parking Sensor :

This Parking sensor works based on the HC SR04 Ultrasonic sensor. The Mbed board sends a 10us pulse on the trig pin of the sensor 
and monitors the echo pin output of the Sensor. 

The duration of the echo level  = time of the wave travelled from the sensor to the object +  time of the wave travelled from object to sensor
distance = time x velocity of sound.

Using this formula, we can calculate the distance of the object (in this case car).

