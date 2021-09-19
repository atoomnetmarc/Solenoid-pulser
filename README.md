# Status

Prototype. Circuit has been validated and know to work on a breadboard, but have not been made into a pcb yet.

# Ding!?

This circuit charges a 2200uF capacitor with a 100 ohm resistor and pulses a 12V JF-0530B solenoid for about 15ms with a NE555 timer chip. The NE555 is configured as a non-retriggerable one-shot timer where the length of the trigger pulse does not matter. The solenoid will strike a reception desk bell to produce a ding sound. The 100 ohm resistor limits triggering to a maximum of once per second. Add a 6mm bushing to the solenoid axle to shorten its throw.

![](Kicad/Solenoid%20pulser-render.jpg)
![](3d/Bell%20holder.png)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)