# Bill Of Materials
- Perfboard
- 12 Gauge Wire, 2 Conductors, Copper Wire 30 ft
- 3S 12V 10A 18650 Lithium Battery Protection Board
- 5A Automotive Fuse
- 2 Momentary LED Switches
- 2 aircraft Guard Safety Switches.
- 1 Latching Key Switch
- Soldering Equipment
- Extra Wire for Connecting Switches (Can be smaller)


# Wiring
Wire according to this schematic. The launch fuse is denoted by an LED.
<img width="803" height="553" alt="Annotated" src="https://github.com/user-attachments/assets/715eb4cb-c3ce-49ae-8cab-0343f422d802" />
<img width="806" height="553" alt="Rocket_Schematic" src="https://github.com/user-attachments/assets/ffaba57e-d4ab-4e10-ab73-8262beb72335" />

The number of switches on the left will depend on the number of toggle switches you have. There will always be two momentary switches in order to comply with rocketry laws. The other requirement is for a continuity LED to show if the fuse is making a connection. That is the highest LED that is wired straight through the igniter and a resistor. There needs to be a resistor to stop the fuse from going off prematurely. The LEDS built into the buttons are all wired to common ground. The lights on the momentary switch act as an armed indicator. The last law requirement is that you must be a certain distance from the launch. 30 ft of 12-gauge wire handles that. It has to be thick so as not to cause too much voltage drop.

## Power Source
I used 3 18650 batteries connected to a management board that will safely output 12V. I used a 5A automotive fuse to protect the circuit. It is also important to insulate the board overall to stop shorts. If you wanted to, you could also add a voltage tester in parallel, but I didn't do that. 
