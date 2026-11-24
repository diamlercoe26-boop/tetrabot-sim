# TETRABOT 3D
### Modular Snake Robot for Search and Rescue Operations

**Reach. Search. Save.**

## Project Overview

TetraBot 3D is an interactive three-dimensional simulation of a modular, snake-like search-and-rescue robot designed to explore hazardous and inaccessible environments.

The concept focuses on using a flexible, interconnected robotic structure to navigate through confined spaces, rubble and collapsed-building environments while identifying potential survivor locations and monitoring simulated environmental hazards.

This project demonstrates the proposed robot's movement behaviour, navigation concept, sensor-monitoring interface and rescue mission workflow through a browser-based 3D simulation.

## Problem Statement

Conventional rescue operations in collapsed structures and disaster-affected environments can expose rescue personnel to unstable structures, restricted access routes and potentially hazardous surroundings.

There is a need to explore robotic systems capable of entering confined spaces, navigating around obstacles and providing useful information about conditions within inaccessible areas.

## Proposed Solution

TetraBot explores a modular snake-robot approach in which multiple interconnected segments form a flexible robotic structure.

The simulation demonstrates how such a robot could navigate through a simulated disaster environment, identify survivor locations and monitor environmental conditions.

## Key Features

- **Modular Structure:** Seven interconnected segments represented in the 3D robot model.
- **Multiple Movement Modes:** Straight, curved and narrow-space movement configurations.
- **Autonomous Navigation:** Simulated route planning through a predefined obstacle environment.
- **Remote Control:** Manual directional control through on-screen buttons or keyboard inputs.
- **Environmental Monitoring:** Simulated gas concentration and temperature readings.
- **Obstacle Awareness:** Calculates the distance to nearby obstacles in the simulated environment.
- **Survivor Identification:** Detects four predefined survivor targets within the simulation.
- **Multiple Camera Perspectives:** Overview, chase camera and robot head-camera views.
- **Mission Console:** Displays survivor status, sensor readings, mission time and event logs.

## Interactive Simulation

Explore the browser-based TetraBot 3D simulation:

**[LAUNCH TETRABOT SIMULATION](https://diamlercoe26-boop.github.io/tetrabot-sim/)**

The simulation allows users to switch between autonomous and remote-control modes, change movement configurations and explore the environment through different camera perspectives.

## Technology Stack

| Technology | Application |
|---|---|
| HTML5 | Webpage structure |
| CSS3 | Interface design and responsive layout |
| JavaScript | Simulation logic and interactive controls |
| Three.js | 3D rendering and visualisation |
| WebGL | Browser-based 3D graphics |

## Simulation Architecture

The simulation consists of four primary functional layers:

1. **Robot Model:** Represents the seven interconnected robot modules and their movement.
2. **Navigation System:** Implements grid-based route planning within a predefined environment.
3. **Environmental Monitoring:** Calculates simulated obstacle distance, gas concentration and temperature.
4. **Mission Interface:** Displays mission progress, survivor identification status and event logs.

## Project Scope and Limitations

The current implementation is a software-based simulation and demonstration.

- Environmental sensor readings are generated from predefined virtual hazard zones.
- Survivor locations are predefined within the simulation environment.
- Autonomous navigation operates within a predefined virtual map.
- Remote control is implemented through browser-based inputs.
- No physical robot, real sensor hardware, wireless communication system or field-tested rescue capability is currently integrated.

The simulation is intended to demonstrate the proposed concept and provide a foundation for further development.

## Future Development

- Physical prototype development.
- Integration of environmental sensors.
- Hardware-based wireless communication.
- Improved navigation and obstacle-avoidance algorithms.
- Testing in controlled confined-space environments.
- Evaluation of modular segment configurations.

## Project Status

**Current Stage:** Interactive 3D software simulation.

Hardware implementation and real-world validation remain future development objectives.

## Repository Structure

```text
tetrabot-sim/
├── index.html
├── README.md
├── docs/
└── assets/
```


Explore our interactive 3D simulation
https://diamlercoe26-boop.github.io/tetrabot-sim/
