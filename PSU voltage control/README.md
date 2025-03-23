**PSU voltage increase and voltage control**  
Based on info found here: https://www.eevblog.com/forum/projects/hp-hstns-pd43-psu-hack-feedback-circuit-(partial)/  

**Overvoltage protection:**  
Add a 4.3KΩ resistor between points OVP1 and OVP2

**Voltage control**  
A 2MΩ potentiometer between 12V and GND, with the wiper connected to the voltage control point gives:  
At 64KΩ we get 10.8 V _not tested under load_  
At 1940KΩ we get 15.5 V  _not tested under load_  
The variation is not linear, it's very flat in the middle, and exponiental at both ends

**Digital voltage control**  
I use a MCP4461-104E/ST 100 KΩ potentiometer, with wipers connected in parallel to 1 MΩ resistors  
Each MCP4461 can control two PSU's
