# Automatic-Street-Light-System

## Overview

This project automatically turns ON a street light when it becomes dark and turns it OFF during daylight. It uses an LDR (Light Dependent Resistor) to detect ambient light and a transistor to control the LED.

## Features

- Automatic ON/OFF operation
- Low power consumption
- Simple and low-cost circuit
- No microcontroller required
- Easy to build for beginners

## Components Used

- LDR (Light Dependent Resistor)
- BC547 NPN Transistor
- LED
- 330 Ω Resistor
- 10 kΩ Resistor
- 9V Battery
- Breadboard
- Connecting Wires

## Working Principle

The LDR changes its resistance according to the surrounding light intensity.

- During daytime, the LDR has low resistance, keeping the transistor OFF, so the LED remains OFF.
- During nighttime, the LDR's resistance increases, allowing the transistor to turn ON and light the LED automatically.

## Circuit Diagram

Add your circuit diagram in the `circuit` folder.

## Applications

- Street lighting
- Garden lights
- Automatic outdoor lamps
- Energy-saving lighting systems

## Future Improvements

- Use a relay to control AC street lights.
- Add solar charging.
- Use an ESP32 or Arduino for IoT monitoring.
- Include motion detection to save more energy.

## Author

Your Name
