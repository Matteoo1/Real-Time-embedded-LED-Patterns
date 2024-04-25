# Real-Time-embedded-LED-Patterns

## Overview

This Arduino project implements real-time LED patterns using FreeRTOS. It showcases synchronized LED animations with two distinct patterns, controlled by interrupts and timers. The system demonstrates efficient task management and timing synchronization for embedded applications.

## Features

- **Real-Time LED Patterns**: Generates synchronized LED animations with two distinct patterns, enhancing visual feedback and demonstration of real-time task execution.
- **Interrupt-Based Control**: Utilizes interrupts to switch between LED patterns, providing responsive and interactive behavior to external events.
- **Timer-Based Animation**: Implements LED animations using FreeRTOS timers for precise timing and synchronization, ensuring consistent and reliable performance.
- **Efficient Task Management**: Demonstrates the capabilities of FreeRTOS in managing concurrent tasks and resources efficiently within an embedded environment.

## Hardware Requirements

- **Arduino Board** (Uno, Mega, etc.)
- **LEDs**: Multiple LEDs connected to digital pins for pattern visualization.

## Software Requirements

- Arduino IDE
- FreeRTOS for Arduino library

## Setup Instructions

1. **Hardware Setup**: Connect LEDs to digital pins 5 to 12 on the Arduino board.
2. **Software Setup**: Open the project in Arduino IDE.
3. **Library Installation**: Ensure the FreeRTOS library is installed in the Arduino IDE.
4. **Upload**: Compile and upload the program to the Arduino board.

## System Operation

- **Initialization**: The system initializes LED pins, interrupts, and timers during setup.
- **Pattern Switching**: Pressing a button connected to pin 3 triggers an interrupt, switching between two LED patterns in real-time.
- **Pattern Animation**: LED patterns are generated using two separate timer callbacks (`pattern1` and `pattern2`), ensuring smooth animation transitions.
- **Interrupt Handling**: The ISR function toggles between the two patterns based on the current state, providing responsive pattern switching behavior.

## Image of the arduino used in the project

<img width="670" alt="image" src="https://github.com/mohamadd10/LED-Control-and-Management-System/assets/119814738/eda0c95d-abf0-47fd-a33b-67173d37ca1b">
