# Hardware Components

## 1. Main Controller
- ESP32 development board
- Acts as the brain of the rover.
- Controls motors, sensors and the cleaning mechanism.
- Provides wireless control through Bluetooth/Wi-Fi.

## 2. Drive System
- 2 or 4 DC geared motors
- Rover wheels
- Motor driver module (L298N or equivalent)
- Enables forward, reverse, left and right movement.

## 3. Cleaning Mechanism
- Rotating brush/roller for collecting roadside waste.
- Servo/DC motor for driving the cleaning mechanism.
- Waste collection tray or removable container.
- Adjustable front cleaning attachment.

## 4. Obstacle Detection
- Ultrasonic sensor
- Detects nearby obstacles such as people, vehicles and objects.
- Helps the operator avoid collisions.

## 5. Power System
- Rechargeable battery pack
- Battery holder/connectors
- Voltage regulation where required
- Separate power paths may be used for motors and control electronics.

## 6. Rover Structure
- Lightweight but strong chassis
- Wheels and motor mounts
- Protective enclosure for electronics
- Removable waste container for easy maintenance.

## 7. Control System
The rover will primarily be operated by a human through a wireless control interface.

Basic controls:
- Forward
- Reverse
- Left
- Right
- Stop
- Cleaning mechanism ON/OFF

## Design Priorities

The hardware should be:
- Compact
- Affordable
- Durable
- Easy to repair
- Easy to operate
- Safe around pedestrians
- Designed so it does not unnecessarily obstruct traffic

## Prototype Approach

The first prototype will focus on basic movement, wireless control, obstacle detection and waste collection.

Additional sensors or automation can be added after testing the basic rover.
