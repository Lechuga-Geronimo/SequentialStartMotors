# Analog-Sequential-Starting-of-three-Single-Phase-AC-Motors

Year: 2011.

Objective: 
To design a completely analogic circuit capable of sequentially starting three single-phase AC motors of 1/4 HP each one.

Specifications: 

* The three AC motors are named as "A", "B" and "C". Each one is activable in a independent manner, powered by a common electrical source of 127V AC at 60 Hz.
* The circuit is conformed by two stages: control circuit and power circuit.
* Both circuits are isolated. 
* Only analogic elements are allowed to conform the circuit (i.e. resistors, capacitors, transistors, diodes) and NE555 timers. Operation Amplifiers are not allowed. * The minimum and maximum number of elements are not specified. The power voltage for control circuit is fixed to 5V. 

For simulation, the software chosen is LiveWire for an early stage, considering Proteus (more specific, Isis) for a definitive version. 

The operation is described as follows:

1.- After 3 seconds of single-pushed one "Start" button, the motor "A" gets operative indeterminately. 
2.- Atfer 5 seconds the motor "A" is activated, the "B" motor starts; indeterminately, as well. 
3.- 10 seconds after the "B" is operating, the "C" gets started. All three motors shall remain operative until a "Stop" button is pushed. 

## Simulation

![416506_466325673384366_1776106834_o](https://github.com/Lechuga-Geronimo/Analog-Sequential-Starting-of-three-Single-Phase-AC-Motors/assets/142461885/e962be50-1e69-4dfb-b814-43a17f2c6cde)
