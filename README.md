# Innovative Electronic Lock System Development Using PIC18F452 Microcontroller

## Project Overview

This project involves the development of an innovative electronic lock system utilizing a PIC18F452 microcontroller, a 4x4 keypad, a solenoid lock, and a relay. The system emphasizes secure access control with advanced features such as a 4-digit PIN input mechanism and an emergency unlock option. The entire system is coded in assembly language for optimal performance.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Hardware Components](#hardware-components)
- [Working Principle](#working-principle)
- [Circuit Diagram](#circuit-diagram)
- [Assembly Code](#assembly-code)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Lock systems are essential for protecting privacy and safeguarding possessions. This project showcases an innovative lock system driven by the PIC18F452 microcontroller, featuring a 4x4 keypad input and an emergency unlock mechanism. This system demonstrates the vital role contemporary lock systems play in securing belongings.

## Features

- **Secure Access Control**: Utilizes a 4x4 keypad for PIN input.
- **Emergency Unlock**: Allows for quick access in case of emergencies.
- **Visual and Auditory Feedback**: LEDs and buzzer indicate access status.
- **Optimized Performance**: Coded in assembly language for precise control.

## Hardware Components

- PIC18F452 Microcontroller
- 4x4 Keypad (Connected to PORTB)
- Red LED (Connected to RD4)
- Green LED (Connected to RD6)
- Buzzer (Connected to RD2)
- 5V Relay (Connected to RD0)
- 12V Solenoid Lock
- Push buttons
- 9V battery with connector
- Resistors (220 ohm)
- Capacitors (100uF, 10uF, 22pF)
- Voltage Regulator IC (LM7805)
- Crystal Oscillator (22Hz)
- Jumper Wires
- Dot Board

## Working Principle

### Solenoid Lock
The solenoid is used as a physical locking mechanism. When the relay is activated, it powers the solenoid, causing it to retract and physically unlock the door. It works on the principle that a current-carrying coil produces a magnetic field near it.

### Relay Control
The relay controls the electrical circuit that powers both the solenoid and the indicator LEDs. When the correct PIN or emergency key is entered, the relay is activated, allowing current to flow to the solenoid and unlocking the door.

### PIN Input System
The 4x4 keypad is used for PIN input. The entered PIN is compared to the predefined PIN or emergency key. If a match is found, the system activates the relay, turns on the green LED, and produces a beep sound. In case of a mismatch, the red LED is activated, and a different beep sound is produced.

### Emergency System
In case of an emergency, a predefined emergency key can access a push button which, when activated, activates the relay, turns on the green LED, and unlocks the door.

## Circuit Diagram


## Assembly Code



