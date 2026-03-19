# LM35DZ-Sample-code
This is an simple Sample code for the LM35 DZ sensor. This code is to be used on an Arduino Nano.
The required materials are: 
* Arduino Nano
* LM35DZ Sensor
* Breadboard
* 104 Ceramic Capacitor
* Led
* Resistor(220 Ohms for best result if not red) 
The pinout is shown in the diagram:
 + LM35DZ middle pin(aka the V Out pin) to Arduino nano Pin A0  
 + LM35DZ left pin(when it's flat side is facing you) to VCC or +5 volts  
 + LM35DZ right pin(Also when it is facing you)to GND        
 + An 104 ceramic capacitor -> Leg 1 to pin V Out of LM35DZ and leg 2 to GND pin of the sensor
 + 5V on the Nano -> + Rail on the BreadBoard  
 + GND on the Nano -> - Rail on the breadboard  
 + Led external anode (or long lead) -> to Nano pin D2  
 + Led external Cathode(or shorter lead) -> to GND via a 220 ohm resistor  
<img width="1224" height="596" alt="image" src="https://github.com/user-attachments/assets/1866dfb9-d7e9-4994-88c1-1669a7af1833" />
<img width="1224" height="596" alt="image" src="https://github.com/user-attachments/assets/2bfb5700-5bde-49b3-a421-e7b8f73c057c" />
