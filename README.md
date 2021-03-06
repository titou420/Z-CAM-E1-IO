# Z-CAM-E1-IO
Controlling the Z CAM E1 through its I/O port.

This repository will hold bits and bobs from my experiments with the Z CAM E1's I/O port
and the API described at https://github.com/imaginevision/Z-Camera-Doc.



The *Focus* folder holds a sketch that shows how to focus the lens with UART commands in different ways.

The *Flash* folder holds a sketch for firing an external flash.

The *RC_PWM* folder holds a sketch that reads PWM input from a model car/boat Radio Control receiver, changes lens focus and takes pictures or starts/stops movie recording based on PWM pulse width.

The *Breadboard* folder contains descriptions of my cabling and breadboard set-up.

For Arduino stuff, I test on a close relative to it, a [Teensy 2.0 by PJRC](https://www.pjrc.com/store/teensy.html).

Teensy 2.0 pinout:
![Teensy 2.0 pinout](Teensy_2_0.png)



