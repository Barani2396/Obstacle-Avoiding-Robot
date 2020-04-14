--------
|ReadMe|
--------

To test the Simulink file attached, add the following addons to the software and configure the hardware corresponding to the connections given below.

---------
|Add-ons|
---------

— Install the following addons by accessing the add-on option located in the menu bar.
		- MATLAB Support Package for Arduino Hardware.
		- Simulink Support Package for Arduino Hardware.
		- Arduino_Engineering_Kit_Support.
		- Simulink library for Arduino Liquid Crystal Display

------------------------
|Arduino pins selection|
------------------------

The 5 major components connected to the Arduino UNO are,
	— Ultrasonic sensor 
	— Servo motor 
	— DC motor and L293D driver
	— LCD display
	— LED (Green) 

— Ultrasonic sensor  
	- Arduino 5V <—> Vcc
	- Arduino gnd <—> gnd
	- Arduino pin 7 <—> trigger pin of ultrasonic sensor
	- Arduino pin 8 <—> echo pin 

— Servo motor
	- Arduino 5V <—> positive pin
	- Arduino gnd <—> gnd
	- Arduino pin 9 <—> third pin of servo motor

— DC motor and L293D driver
	- L293D driver positive pin <—> DC motor positive pin
	- L293D driver negative pin <—> DC motor negative pin
	- Arduino 5V <—> L293D drive pins 1, 8, 16 & 19
	- Arduino gnd <—> L293D drive pins 4, 5, 12 & 13
	- Arduino pin 5 <—> L293D driver pin 2
	- Arduino pin 6 <—> L293D driver pin 7

— LCD
	- Arduino 5V <—> LCD pin 1 & 15
	- Arduino gnd <—> LCD pin 2 & 16
	- Arduino pin 3 <—> LCD pin 4
	- Arduino pin 2 <—> LCD pin 6
	- Arduino pin 10 <—> LCD data pin 
	- Arduino pin 11 <—> LCD data pin
	- Arduino pin 12 <—> LCD data pin
	- Arduino pin 13 <—> LCD data pin
	- LCD pin 3 <—> potentiometer positive
	- LCD pin 5 <—> potentiometer gnd

— LED
	- Arduino pin 4 <—> 220ohm resistor <—> LED positive pin
	- Arduino gnd <—> LED gnd 
