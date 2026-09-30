# CDFR2027-PAMIs-ELEC

![ESP32 WROOM S3](https://img.shields.io/badge/ESP32-WROOM%20S3-005f73?style=for-the-badge&logo=esphome) ![KiCad](https://img.shields.io/badge/KiCad-Design-1a73c5?style=for-the-badge&logo=kicad) ![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=for-the-badge)

PCBs for Eurobot's 2027 SIMAs.

This repository contains the KiCad design files for the electronic boards developed for the Robotronik Eurobot 2027 project. It includes modular PCB projects for the robot control and processing architecture, centered around ESP32 WROOM S3-based hardware.

## Overview

The project is organized into separate board designs:

- `ControlBoard/` — main control electronics board and associated KiCad schematics/PCB
- `BrainBoard/` — brain board project and related documentation

## Current status

This repository is currently under active development. Schematics, layouts, and interfaces may evolve as the hardware design is refined and validated.

## Design workflow

- Open the KiCad project files (`*.kicad_pro`) in KiCad 8+
- Review schematics and PCB layout in the corresponding board folders
- Use the design files as the source of truth for revisions and manufacturing outputs

## Repository structure

```text
.
├── BrainBoard/
│   └── README.md
├── ControlBoard/
│   ├── CDFR2027-PAMIs-ELEC-control.kicad_pro
│   ├── CDFR2027-PAMIs-ELEC-control.kicad_sch
│   ├── CDFR2027-PAMIs-ELEC-control.kicad_pcb
│   ├── power.kicad_sch
│   ├── io.kicad_sch
│   ├── motors.kicad_sch
│   ├── actuators.kicad_sch
│   └── ...
├── README.md
└── LICENSE (if added later)
```

## Notes

This repo is intended for PCB development and hardware iteration for the 2027 Eurobot competition. Contributions, schematic updates, and board revisions should be tracked in the corresponding board folders.
