# speeddetector
Arduino car speed detector

IR Sensors are the main part of the project that detect the speed of a car. Practically, you can implement the setup of IR Sensors in many ways but in this project, we have used two reflective type IR Sensors and placed them 10cm apart.
When a car travelling reaches the first sensor, the IR Sensor gets activated. From this moment onward, a timer is initiated and will continue to keep time until the car reaches the second IR Sensor.
By simulating the distance between the two sensors to be 5 meters, you can calculate the speed at which the car travelled from IR Sensor 1 to IR Sensor 2 as you already know the time of travel.
All the calculations and data gathering are done by Arduino and the final result is displayed on a 16X2 LCD Module.
