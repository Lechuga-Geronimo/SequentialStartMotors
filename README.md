# Analog-Sequential-Starting-of-three-Single-Phase-AC-Motors

A project to start three single-phase AC motors in a timed and specific sequence. 

## Year: 2011.

## Objective: 
To design a completely analogic circuit capable of sequentially starting three single-phase AC motors of 1/4 HP each one.

## Specifications: 

* The three AC motors are named as "A", "B" and "C". Each one is activable in a independent manner, powered by a common electrical source of 127V AC at 60 Hz.
* The circuit is conformed by two stages: control circuit and power circuit.
* Both circuits are isolated.
* The power voltage for control circuit is fixed to 5V. 
* Only analogic elements are allowed to conform the circuit (i.e. resistors, capacitors, transistors, diodes, etc.), basic integrated circuits (AND, OR, NAND, NOR, NOT) and NE555 timers. Operation Amplifiers are not allowed.
* The minimum and maximum number of elements are not specified.

The operation is described as follows:

1.- After 3 seconds of single-pushed one "Start" button, the motor "A" gets operative indeterminately. 

2.- Atfer 5 seconds the motor "A" is activated, the "B" motor starts; indeterminately, as well. 

3.- 7 seconds after the "B" is operating, the "C" gets started. All three motors shall remain operative until a "Stop" button is pushed, or...

4.- After 10 seconds the "C" motor started, the sequence will restart from step 1, with the exception of not being necessary to push the "Start" button. 

Note: The "Stop" button may be pushed in any step or moment and still shall be effective. 

## Simulation

An early effort was made in LiveWire.

![470344_456237211059879_1952931227_o](https://github.com/Lechuga-Geronimo/Analog-Sequential-Starting-of-three-Single-Phase-AC-Motors/assets/142461885/3f03fcdb-876f-466b-8b00-adec5fd545de)

However, for final and definitive simulation, Proteus (more specific, Isis) is chosen. 

![416506_466325673384366_1776106834_o](https://github.com/Lechuga-Geronimo/Analog-Sequential-Starting-of-three-Single-Phase-AC-Motors/assets/142461885/e962be50-1e69-4dfb-b814-43a17f2c6cde)
