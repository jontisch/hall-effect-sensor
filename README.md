# hall-effect-sensor
A Hall Effect measurement system for measuring power/amperage for graphing

This uses the circuit described in the eagle/gerber directory. 
We've used dirtypcbs.com to make them (http://dirtypcbs.com/view.php?share=27748&accesskey=)

The code used is in arduino/src
It is dependant on 
https://github.com/sirleech/TrueRandom
https://github.com/openenergymonitor/EmonLib 
https://github.com/ntruchsess/arduino_uip (which in turn is patched to support sending DHCP Client Identification which is why it is included in arduino/src)

Hall effect sensors used are SCT-013-000.
