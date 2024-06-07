# Bike-Turning-Signal-Circuit-
The objective of this circuit is to indicate left or right turn for bike/vehicle. The main component of this circuit is the infamous 555 Timer IC. Here, this 555 timer acts as an Astable multi vibrator. It generates the pulse signal with variable width. Using this variable width of the pulse, we can set different time delays for the LEDs (ON and OFF for LEDs).

The circuit consists of two important resistors (100KΩ and 470KΩ), which are connected to 555 timer and these are used to set the time delay for LEDs. The output of the 555 Timer IC is given to either LEFT indicator LED or the RIGHT Indicator LED using a Slide Switch. 

1n4148 signal diode is connected in reverse bias at the output to maintain constant current at the output. BC547 (NPN) Transistor switches the LED’s ON and OFF based on the base currents. 330 ohm resistors are used to drop the voltage otherwise LEDs may get damaged. Here we can vary the time width of output pulse by varying the resistance or capacitance value.
