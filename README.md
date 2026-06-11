# Elevator Controller

## Overview

This project implements a Finite State Machine (FSM) based Elevator Controller for a multi-story residential building.

The controller manages elevator movement between floors, processes floor requests, controls door operations, and maintains safe elevator sequencing through state-based control logic.

---

## Multi-Story Building Layout

![Building Layout](Images/building_layout.png)

The building consists of:

- Basement (B)
- Ground Floor (G)
- First Floor (1)
- Second Floor (2)
- Third Floor (3)

A single elevator services all five levels.

---

## System Features

- Single elevator car
- Five serviceable levels (B, G, 1, 2, 3)
- Hall call buttons (UP / DOWN)
- Internal floor selection buttons
- Automatic door control
- Floor position tracking
- FSM-based control architecture

---



---

## Inputs

### Hall Requests
- UP Button
- DOWN Button

### Cabin Requests
- Basement (B)
- Ground Floor (G)
- Floor 1
- Floor 2
- Floor 3

---



## Future Work

- Verilog RTL implementation
- Testbench development
- Functional simulation
