# Arduino pulse sensor device

This device gathers the data regarding heartbeat/Pulse/BPM rate, and displays it to user on LCD display.

## Materials required
*	Pulse sensor
*	LCD 16X2
*	Arduino UNO

## Working rule

*	When a heartbeat occurs, blood is pumped through the human body and gets squeezed into the capillary tissues. Consequently, the volume of these capillary tissues increases. But in between the two consecutive heartbeats, this volume inside capillary tissues decreases. This change in volume between the heartbeats affects the amount of light that will transmit through these tissues. This can be measured with the help of a microcontroller.
*	The pulse sensor module has a light that helps in measuring the pulse rate. When we place the finger on the pulse sensor, the light reflected will change based on the volume of blood inside the capillary blood vessels. This variation in light transmission and reflection can be obtained as a pulse from the output of the pulse sensor. This pulse can be then conditioned to measure heartbeat and then programmed accordingly to read as heartbeat count using Arduino.

## Circuit
![alt text](https://github.com/abhineetraj1/arduino-pulse-sensor/blob/main/image.png?raw=true)

## Installation
* Download Arduino IDE.
* Open main.ino file and upload the code into arduino board.
* Attach tft display to arduino board
* Run your Arduino :)

## Programming languages used:-
<a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40">


## Author
*	[abhineetraj1](http://github.com/abhineetraj1)