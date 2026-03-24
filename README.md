# BLDC-Drone
## Overview
This project is a custom-built quadcopter drone powered by four brushless DC (BLDC) motors. The system is designed around an STM32 microcontroller, which handles real-time motor control using a custom sensorless control algorithm. The goals of this project are to develop a compact and efficient drone platform with fully in-house hardware and firmware design, to explore the concept of BLDC motor control, and to fulfill my bitter regrets of not being able to make a functional drone for the 2026 Southeast Con Hardware Competition.
## Features
- STM32-based flight control system for precise and responsive operation
- Sensorless BLDC motor control (no Hall effect or other sensors required)
- Custom hardware design, including schematics and PCB layouts
- Integrated 3D models for mechanical components and assembly
## Repository Structure
- /hardware
  - Contains all physical design files for the drone:
    - KiCad schematics and PCB layouts
    - 3D models for structural and mounting components
- /software (planned, not implemented yet)
  - Will include firmware and control algorithms for the STM32, including motor control and flight logic
## Project Milestones
- Develop a reliable sensorless BLDC control system
- Design and fabricate a fully custom drone PCB
- Integrate hardware and software into a stable flight platform
- Provide a modular foundation for future improvements (ex: sensors, autonomy, communication systems)
## Status
This project is currently in active development. Hardware designs are available but are subject to change, and software development is ongoing.
