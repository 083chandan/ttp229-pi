# ttp229-pi

Interfacing the TTP229 using two wires with Raspberry Pi 3 using python.

TTP229 is used as 16 key mode.
 
## Hardware and Software Required


* TTP229 Capacitive Touch Sensor Module
* Raspberry Pi 3 Model B/B+

## Input Keys Number Select Mode
The TTP229-BSF has 8 keys input mode and 16 keys input mode. These modes are selected via high-value resistor connected to the TP2(KYSEL) pin to VSS, or not. The default that TP2(KYSEL) pin is not used resistor connected to VSS is selected 8 keys input mode. Another is selected 16 keys input mode that has used a high-value resistor connected to VSS.

* TP2(KYSEL)- 1 - 8 input keys mode(Default)
* TP2(KYSEL)- 0 - 16 input keys mode
 
`Note:To enable 16 keys mode,short the key as shown in the image before switch on the module and the user can directly use the OUT1 to OUT8 pins for 8 keys mode(default).`