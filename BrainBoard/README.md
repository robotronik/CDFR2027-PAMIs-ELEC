# BrainBoard

![ESP32 WROOM S3](https://img.shields.io/badge/ESP32-WROOM%20S3-005f73?style=for-the-badge&logo=esphome) ![KiCad](https://img.shields.io/badge/KiCad-Design-1a73c5?style=for-the-badge&logo=kicad) ![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)

The BrainBoard is the strategy and supervision layer of the robot. It is responsible for high-level decision-making, coordination, and communication with the lower-level actuation and motion systems.

This board is designed to host the robot's central intelligence and provide the interfaces needed for autonomous behavior, sensor processing, and command orchestration.

## Role in the robot

The BrainBoard acts as the "brain" of the system:

- Runs robot strategy and autonomous behavior
- Coordinates actions with the ControlBoard
- Processes sensor and perception data
- Manages high-level state and mission logic
- Supervises communication with lower-level subsystems

## Main responsibilities

- Central processing and robot state management
- Strategy selection and tactical decision-making
- Sensor data acquisition and interpretation
- Command generation for motion and actuator tasks
- Supervisory logic and safety coordination

## Hardware focus

This board is intended to be built around the ESP32 WROOM S3 platform and designed in KiCad, with the interfaces required for a modern competition robot architecture.

## Relationship with the ControlBoard

The BrainBoard handles strategic logic and orchestration, while the ControlBoard handles direct motion execution, actuator control, drive systems, and power distribution.

## Related project

- `../ControlBoard/` — drive control, actuator management, and power electronics
- `../README.md` — repository overview

## Status

In development.
