# Motion-Activated Security Light

## Project Overview
This project uses an Arduino UNO and PIR motion sensor to create a motion-activated security light using Tinkercad.

## Components Used
- Arduino UNO
- PIR Motion Sensor
- LED
- Resistor
- Connecting wires
- Tinkercad Simulator

## Working Principle
1. The PIR sensor detects movement.
2. When motion is detected, it sends a HIGH signal to Arduino.
3. Arduino turns ON the LED.
4. When no motion is detected, Arduino turns OFF the LED.

## Pin Connections
- PIR OUT → Arduino D2
- PIR VCC → 5V
- PIR GND → GND
- LED → Arduino D13 through a resistor

## Sensor Reading Interval
200 milliseconds.

## How to Run
1. Open the Tinkercad circuit.
2. Start the simulation.
3. Trigger the PIR sensor.
4. Observe the LED response.

## Expected Output
- Motion detected: LED ON
- No motion detected: LED OFF

## Tools Used
- Arduino UNO
- Tinkercad Circuits
- Arduino C++

## Project Level
Embedded Systems & IoT – Level 1: Sensor and Actuator
