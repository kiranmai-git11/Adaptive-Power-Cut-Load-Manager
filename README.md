# Adaptive Power Cut Load Manager (ESP32)

This project is an implementation and simulation of an Adaptive Power Cut Load Management system using ESP32.
The work focuses on understanding priority-based load control and implementing it using serial input.

## Project Type
- Academic / Learning Project
- Implementation & Simulation based

## Description
Based on power availability levels (High, Medium, Low), loads are turned ON or OFF according to priority.
The system was implemented and tested using ESP32 and LEDs as load indicators.

## Power Modes
- **High (H):** All loads ON
- **Medium (M):** Essential loads ON
- **Low (L):** Only critical load ON

## Components Used
- ESP32
- 4 LEDs
- 4 × 220Ω resistors
- Jumper wires

## Implementation Details
- Serial Monitor input (H / M / L)
- Priority-based decision logic
- Debugged wiring and serial input issues
- Simulated using Wokwi

## Learning Outcome
- ESP32 GPIO control
- Serial communication handling
- Hardware debugging
- Load priority logic

## Author
Kiranmai
