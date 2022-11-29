# ZLight_CC2652
A light and a PIR handled by Zigbee

The firmware is made for a CC2652RB and CC2652P TI chips and it is avaiable under the firmware folder.
The first version was for E72-2G4M05S1F (CC2652RB) module but for his shortage, I migrated to the E72-2G4M05S1E module, based on CC2652P1F chip.

For licence issue, I can't put the sources, but you can request at me (pachdjian@gmail.com)

Into firmware folder there are both the firmware.
Into Box, there is a Freecad model for a box I made
Into Schematic thare is two versions on a KiCad circuit with a PCB layout. 
 * The first version is for a E72-2G4M05S1F and it is without a PIR connector.
 * The second version is for a E72-2G4M05S1E module, it contains some fixes and enanchements 


# Instruction



The power supply is 12 Volts. The maximum limits is set by the LM1117 chip that has a maximum input value of 15 Volts.
The PIR used is a AS312, but there are a plenty of others PIR sensors. The important thing is that it should be power by 3.3 volt and a digital output.

The consume is about 0.4 - 0.5 A, so the maximum  emitted light is about 5-6 Watt.
It implement a On/Off and Controll cluster, so you can reduce the luminosity.

The first time the ZLight start it search for a available network.
The two leds blink alternately.

If you need to reset the network, press button 1 for more that 5 seconds.

Then the ZLight will be reset the network configuration and it will begin to search for a new network, blinking the two leds

