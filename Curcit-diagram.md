# Circuit Diagram – Smart Road Cleaning Rover

## 1. Main Components

- ESP32 development board
- Battery / power supply
- Motor driver module (L298N or equivalent)
- DC geared motors and wheels
- Cleaning motor and rotating brush
- Ultrasonic sensor

## 2. Connection Overview

| Component | Connected To | Purpose |
|---|---|---|
| ESP32 | Motor driver control inputs | Controls rover movement |
| Motor driver | Drive motors | Drives the wheels |
| ESP32 | Cleaning motor control circuit | Controls the cleaning mechanism |
| Ultrasonic sensor | ESP32 | Detects nearby obstacles |
| Battery | Power system | Supplies electrical power |

## 3. Important Notes

- Use a suitable motor driver for the motors being used.
- The motor power supply must match the motor voltage and current requirements.
- Connect the ESP32 and motor driver grounds together when required by the circuit.
- Do not connect motors directly to ESP32 GPIO pins.
- Check the ESP32 board's voltage requirements before connecting power.

## 4. Actual Wiring Diagram

Add the final circuit diagram here after confirming the exact components, pin numbers, and power supply.

*Note: This is a connection overview, not a verified pin-by-pin wiring diagram.*
