# Clap detector (0002)

Clap-detecting switch

## Description

This circuit is a copy of [AVT-721/2](./AVT721_2.pdf) converted to Surface Mounted Technology.

<img src="images/schematic.png" alt="Schematic" style="width:600px;"/>

## Assembly

The circuit should be assembled on a double-sided, SMT printed circuit board.

<img src="images/pcb_front.png" alt="PCB front layout" style="width:600px;"/>

<img src="images/pcb_back.png" alt="PCB back layout" style="width:600px;"/>

## Running

The device should be powered with 6-10DCV. It was intended to be powered from 6F22 9V battery connected to J1 connector.
The circuit after detecting a clap, switches D1 diode on and off. Additionally, it enables/disables K1 relay. A device
of max 230V/1000W can be enabled/disabled using J2 connector. 