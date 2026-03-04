# Autonomous-Horse-Carriage-Design
Design of a mechanically-driven **autonomous horse carriage platform**, combining traditional carriage form with modern robotics and autonomous navigation technologies.

This project was developed as a **Bachelor's Graduation Design Project** in the School of Electrical and Control Engineering, North China University of Technology.

---

# Project Overview

This project proposes a robotic transportation platform inspired by traditional horse-drawn carriages while integrating modern control systems and autonomous navigation.

The system combines:

- Mechanical structure design
- Embedded control system
- GPS-based navigation
- Autonomous steering mechanism

Key technologies used in this project include:

- **SolidWorks** for mechanical design and simulation
- **APM 2.8 autopilot** for autonomous navigation
- **STM32F103C8T6** embedded controller
- **GPS waypoint navigation**

The carriage can automatically follow predefined paths and execute steering commands at target waypoints.

---

# System Architecture

The system consists of three main subsystems:

## Mechanical Structure

The carriage structure was designed using **SolidWorks**, including:

- Horse body frame
- Locomotion mechanism
- Steering mechanism
- Internal hardware layout

Two design variants were proposed:

1. Integrated horse carriage
2. Trailer-style horse carriage

The horse legs adopt a **Theo Jansen linkage mechanism** to simulate natural horse motion.

---

## Control System

The control architecture includes:

| Component | Function |
|---|---|
| APM 2.8 Autopilot | Navigation and waypoint planning |
| STM32F103C8T6 | Main controller |
| M8N GPS Module | Positioning |
| Relay Module | Actuator control |
| DC Brushless Motor | Vehicle propulsion |
| Electric Linear Actuator | Steering control |

The autopilot receives GPS position data and sends control commands to the STM32 controller.

---

## Autonomous Navigation

Navigation is implemented using:

- GPS waypoint navigation
- Distance calculation using the **Haversine formula**
- Heading angle calculation
- Relay-controlled steering actuators

When the vehicle reaches a target waypoint, the STM32 controller triggers steering actions through linear actuators.

---

# Software Tools

The following tools were used in this project:

- **SolidWorks** – Mechanical design and motion simulation
- **STM32CubeMX** – Peripheral configuration
- **Keil uVision5** – Embedded software development
- **Mission Planner** – APM autopilot configuration

---

# Demonstration

## Demo 1 — Autonomous Driving

<!-- Replace the link below with your demo video or gif -->
![Demo1](demo/demo_autonomous_drive.gif)

---

## Demo 2 — Steering Mechanism

<!-- Replace the link below with your demo video or gif -->
![Demo2](demo/demo_steering.gif)

---

# Code Availability

The embedded control software used in this project belongs to the laboratory where the project was conducted.

Therefore, **the source code cannot be publicly released in this repository**.

Only mechanical design files, documentation, and demonstration materials are provided.

---

# Author

Ruihan Wang  
School of Electrical and Control Engineering  
North China University of Technology
