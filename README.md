# ZLight_CC2652RB
A light and a PIR handled by Zigbee

The firmware is made for a CC2652RB TI chip and it is avaiable under the firmware folder.

For licence issue, I can't put the sources, but you can request at me (pachdjian@gmail.com)

The PCB is for the module E72-2G4M05S1F by EBYTE.

# Instruction

The power supply is 12 Volts. The maximum limits is set by the LM1117 chip that has a maximum input value of 15 Volts.
The consume is about 0.4 - 0.5 A, so the maximum  emitted light is about 5-6 Watt.
It implement a On/Off and Controll cluster, so you can reduce the luminosity.


The first time the ZLight start it search for a available network.
The two leds blink alternately.

If you need to reset the network, press button 1 for more that 5 seconds.
Then the ZLight will be reset the network configuration and it will begin to search for a new network, blinking the two leds

