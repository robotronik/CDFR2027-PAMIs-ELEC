# ControlBoard

![ESP32 WROOM S3](https://img.shields.io/badge/ESP32-WROOM%20S3-005f73?style=for-the-badge&logo=esphome) ![KiCad](https://img.shields.io/badge/KiCad-Design-1a73c5?style=for-the-badge&logo=kicad) ![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)

The ControlBoard is the low-level power and motion board of the robot. It is responsible for drivetrain control, actuator command management, IO handling, and the electrical interfaces required to move and operate the robot reliably.

This board is the execution layer of the robot architecture: it receives commands from the BrainBoard and converts them into motion, switching, and actuator behavior.

## Role in the robot

The ControlBoard focuses on the physical actuation layer:

- Motor drive and motion control
- Actuator control and PWM management
- Power distribution and regulation
- Digital/analog I/O interfaces
- Safety and command routing from the brain layer

## Key areas covered

The KiCad project is structured around several functional blocks:

- `power.kicad_sch` — power input, regulation, and distribution
- `motors.kicad_sch` — drivetrain motor interfaces and driver electronics
- `actuators.kicad_sch` — actuator control and related outputs
- `io.kicad_sch` — general-purpose I/O and interfacing
- `CDFR2027-PAMIs-ELEC-control.kicad_sch` — main schematic integration

## Typical responsibilities

- Driving the robot's wheels and movement systems
- Controlling servos, actuators, and mechanism outputs
- Managing switching and I/O states
- Distributing power to the vehicle subsystems
- Translating commands from the higher-level strategy layer into real hardware actions

## Board purpose

This board handles the operational part of the robot, while the `BrainBoard` handles higher-level strategy and coordination.

## Related project

- `../BrainBoard/` — central strategic logic and robot intelligence
- `../README.md` — repository overview

## Status

In development.
