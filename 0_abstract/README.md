# abstract
In this project we are going to design a circuit for measuring temperature. This circuit is developed using “LM35”, a linear voltage sensor. Temperature is usually measured in “Centigrade” or “Faraheite”. “LM35” sensor provides output based on scale of centigrade. LM35 is three pin transistor like device. It has VCC, GND and OUTPUT. This sensor provides variable voltage at the output based on temperature.


# Detail requirements
## High Level Requirements: 
A digital thermometer is a good project in microcontrollers because it provides an opportunity to learn using sensors to measure the real world signals that are analog in nature. I am trying to describes a similar project based on a Atmega32 microcontroller and an LM35 temperature sensor. LM35 is an analog sensor that converts the surrounding temperature to a proportional analog voltage. The output from the sensor is connected to one of the ADC channel inputs of the Atmega32 microcontroller to derive the equivalent temperature value in digital format. The calibrated temperature is displayed in a 16×2 character LCD, in both °C and °F scales.


##  Low level Requirements:
Low Plan for the temperature measurment using LM35 sensor is that we can use another sensor and lower cost sensor such as DHT11 for temperature measurment. Another option is to replace the board to  the low cost board.




.
