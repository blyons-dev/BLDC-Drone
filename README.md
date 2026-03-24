# BLDC-Drone (Arduino + ESC Version)
## Overview
This branch of the BLDC Drone project focuses on rapid development of flight control algorithms using an Arduino Nano and off-the-shelf Electronic Speed Controllers (ESCs).
Unlike the main version, which implements a custom sensorless BLDC control system, this approach leverages prebuilt ESCs to handle motor communication. This allows development efforts to concentrate on higher-level flight dynamics such as stabilization, hovering, and maneuverability.
## Purpose
The goal of this branch is to provide a simplified and accessible platform for developing and testing flight control systems while the custom motor control hardware and firmware are still under development. By abstracting away low-level motor control, this version enables faster iteration on control algorithms.
## Features
- Arduino Nano-based controller for ease of use and rapid prototyping
- ESC-driven BLDC motors for reliable and simplified motor control
- PWM-based motor interface, compatible with standard drone ESCs
- Modular design that mirrors the main project architecture wherever possible
## Repository Structure
- /hardware
  - Contains supporting hardware files:
    - Wiring diagrams and integration notes for Arduino + ESC setup
    - Any shared mechanical components (frames, mounts, etc.)
- /software (Planned)
  - Containes Arduino-based firmware:
    - Flight Control Algorithms (PID, stabilization, etc.)
    - ESC control via PWM signals
    - Sensor integration (ex: IMU, if included)
## Key Differences from Main Branch
| Feature           | Main Branch (STM32)              | This Branch (Arduino + ESC)    |
| ----------------- | -------------------------------- | ------------------------------ |
| Motor Control     | Custom sensorless BLDC control   | Off-the-shelf ESCs             |
| Microcontroller   | STM32                            | Arduino Nano                   |
| Development Focus | Low-level motor control + flight | High-level flight control only |
| Complexity        | High                             | Moderate / Beginner-friendly   |
## Project Milestones
- Develop stable flight control algorithms (PID loops for roll, pitch, yaw)
- Achieve controlled hovering and basic maneuverability
- Create a testbed for validating control strategies before porting to STM32
- Maintain compatibility with the main project architecture wherever possible
## Status
This branch is intended for active experimentation and rapid prototyping. It may evolve quickly as control strategies are tested and refined.
