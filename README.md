# Active Sensor Stabilization Platform (ASSP)

> Design, simulation, and development of a two-axis active sensor stabilization platform for autonomous maritime sensing applications.

---

## Overview

The Active Sensor Stabilization Platform (ASSP) is an engineering portfolio project developed under **Orion Dynamics** to demonstrate the complete hardware development lifecycle for an embedded electromechanical system.

The project simulates a stabilized sensor payload for an Autonomous Surface Vessel (ASV), using inertial sensing, closed-loop control, and a two-axis gimbal to compensate for vessel pitch and roll.

Rather than focusing solely on the final prototype, this repository documents the engineering process from concept through verification.

---

## Objectives

- Design a two-axis gimbal capable of stabilizing a camera or mock LiDAR payload.
- Develop embedded firmware using an ESP32 microcontroller.
- Implement closed-loop PID control using IMU feedback.
- Design the mechanical structure in CAD.
- Develop electrical schematics and power distribution.
- Validate system performance through testing and data analysis.
- Produce professional engineering documentation throughout development.

---

## Project Status

| Phase | Status |
|--------|--------|
| Requirements | 🟡 In Progress |
| System Architecture | ⬜ Not Started |
| Trade Studies | ⬜ Not Started |
| CAD Design | ⬜ Not Started |
| Electrical Design | ⬜ Not Started |
| Firmware Development | ⬜ Not Started |
| Prototype Assembly | ⬜ Not Started |
| Testing & Validation | ⬜ Not Started |

---

## Planned System Architecture

```
Motion Disturbance
        │
        ▼
      IMU Sensor
        │
        ▼
      ESP32 MCU
        │
   PID Controller
        │
        ▼
 Servo Actuation
        │
        ▼
 Two-Axis Gimbal
        │
        ▼
 Camera / LiDAR Payload
```

---

## Repository Structure

```
docs/            Engineering documentation
cad/             Mechanical CAD models
electrical/      Schematics and power design
firmware/        Embedded software
simulation/      MATLAB/Python simulations
media/           Photos, videos, and demonstrations
```

---

## Engineering Process

This project follows a systems engineering approach similar to those used in robotics, aerospace, and defense programs.

1. Requirements Definition
2. Concept of Operations
3. System Architecture
4. Trade Studies
5. Mechanical Design
6. Electrical Design
7. Embedded Software Development
8. Prototype Integration
9. Verification & Validation
10. Final Design Review

---

## Tools

- Autodesk Inventor
- Visual Studio Code
- PlatformIO
- ESP32
- Git & GitHub
- Microsoft Word
- Microsoft Excel
- Python

---

## License

This project is released under the MIT License.

---

**Project Lead:** Jacob Crihfield  
**Organization:** Orion Dynamics