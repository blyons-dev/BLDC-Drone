# KiCAD Setup

## Installation
1. Download KiCAD from the official website.
2. Follow the installation instructions for your operating system.

## Configuration
1. Open KiCAD and go to `Preferences` → `Configure Paths`.
2. Set additional libraries as needed for your project.

# Project Structure

The recommended project structure for the BLDC Drone hardware design is as follows:

```
BLDC-Drone/
├── schematics/
│   └── main.kicad_sch
├── pcb/
│   └── main.kicad_pcb
├── libs/
│   └── custom_lib.pretty
└── README.md
```

- **schematics/**: Contains the KiCAD schematic files.
- **pcb/**: Contains the PCB layout files.
- **libs/**: Custom libraries used in the project.

# Version Information

- KiCAD Version: [Insert KiCAD Version]
- Last Updated: 2026-03-23

Ensure to keep your KiCAD and all libraries updated to the latest stable versions for compatibility and access to new features.