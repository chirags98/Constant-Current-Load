# Constant-Current-Load

This circuit uses an opamp and a mosfet as a voltage follower circuit. I can dial in any current I want and the circuit will adjust itself to draw that much current from the power supply regardless of the supply voltage. It can be 3 Volts, 5 Volts, 15 Volts whatever it might be and the load will adjust itself to draw the selected current.

This is a double sided board design which I got manufactured from a PCB prototyping firm in China.

I designed the circuit to have the following features

* To have a knob to vary the current from 1mA-2A
* Dissipate upto 30 watts of power
* Connect a supply upto 30 volts
* To have a LCD panel to show 
    * Current drawn
    * Voltage across the load
    * Power dissipated in the load
* Give warnings if power/current/voltage range are excedded
* Give the user the choice to run the circuit from the load supply thereby eliminating the need for an external power supply
