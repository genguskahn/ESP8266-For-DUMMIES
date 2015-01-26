# ESP8266-For-DUMMIES.
Minimum set of files to use ESP8266 in WINDOWS.

This contains the bare minimum to allow the use of ESP8266.



.
.
The Folders are ....
.
.
.

>>>>>>>>>>>

AT for the "AT Command Set" and Arduino IDE.





SoC for the Lua loader Autonomous version.





Use the Onboard system processor to completely replace the Arduino and run code DIRECTLY from the device.

I have added a single SS88050 transistor to the GPIO_0 output and I use a served webpage from the
device to PWM control over 4 meters of White 3528 12v LEDs via WiFi.

Total Cost Less than £10

Including 3V LDO, 5v 7805, 2 10uF, Wire, Box, Transistor AND the ESP8266 !!!

Cheap 12V Power £1 (from CN), cheap 5 Meter strip of 3528 LEDs £3 (from CN).

Using GPIO_0 even when I upgrade the firmware it has the result of switching OFF the LEDs during UPGRADE........




ESP8266-XX          Wiring ----

For Normal MODE .....

CH_PD --> Vcc (POWER DOWN Mode if floating or Gnd)

Vcc   --> 3V (use seperate LDO, 5 for £2)

Gnd   --> Gnd

Tx    --> Rx

Rx    --> Tx


For Firmware UPDATE MODE ....

As Above PLUS GPIO_0  --> Gnd (Flash Write UN-Protect/UPGRADE MODE).

