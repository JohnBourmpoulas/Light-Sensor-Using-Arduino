# Light-Sensor-Using-Arduino
The Project is about switching on the light if necessary (i. e in darkness) and switching off the light when there is enough brightness.


Steps:
Connect the 3.3V of arduino to the positive rail and ground to the negative rail of breadboard.

Connections for LDR sensor:
Place the LDR on the breadboard and attach the 10k ohm resistor to one of the legs of LDR. Connect the A0 pin of arduino to the same column of resistor and LDR.
This is to fetch the intensity of light from LDR to the arduino through A0 pin.
Connect the other end of resistor to the negative rail of breadboard.
Connect the other end of LDR to the positive rail of breadboard.

Connections for LED:
Place LED on breadboard and connect positive end of LED to the 220ohm resistor.
Connect the other end of resistor to the pin 13 of arduino.
Connect the negative end of LED to the negative rail of breadboard.


The setup is now ready. Now load the code in Arduino IDE and then upload it to Arduino. Check the light intensity near LDR. Try changing the Brightness of light near LDR sensor.


![image](https://user-images.githubusercontent.com/46540325/165391024-04f0f339-169d-4430-9f16-d3c8e33bcb9f.png)
