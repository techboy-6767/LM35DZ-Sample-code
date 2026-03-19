# LM35DZ-Sample-code
This is an simple Sample code for the LM35 DZ sensor. This code is to be used on an Arduino Nano.
The required materials are: 
* Arduino Nano
* LM35DZ Sensor
* Breadboard
* 104 Ceramic Capacitor
* Led
* Resistor(220 Ohms for best result if not red)
We also need the input voltage to be exact 5 volts for this code to work, else you need to change the line 45 to -> float milliVolts = (avgRaw * x) / 1024.0; (change x to the value measured by using an multimeter)
The pinout is shown in the diagram:
<img width="1045" height="662" alt="image" src="https://github.com/user-attachments/assets/4a8c0e7f-cc58-42a4-8f26-7fc0adaff297" />
<img width="1224" height="596" alt="image" src="https://github.com/user-attachments/assets/417b261c-be18-4c01-9559-ab32eb28ba7f" />
The pinout step by step can be seen in an video of my channel:@techboy6373
