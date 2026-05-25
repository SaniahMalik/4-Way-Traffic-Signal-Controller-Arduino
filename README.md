# 4-Way-Traffic-Signal-Controller-Arduino
A microcontroller-based 4-Way Traffic Signal Controller System designed and simulated in Tinkercad using Arduino Uno and C++ programming.
# 4-Way Traffic Signal Controller System (Arduino Simulation)

## Project Overview
This project presents the core controller logic and hardware implementation mapping for an intelligent **4-Way Traffic Signal Controller System** simulated via **Tinkercad**. Developed as part of our Digital Logic Design (DLD) lab curriculum, the system model manages safe transit sequencing across urban intersections using automated time delay loops.

## Components & Circuit Map
* **Microcontroller:** Arduino Uno R3
* **Display Indicators:** 12 Light Emitting Diodes (4 Red, 4 Orange, 4 Green)
* **Resistors:** 12 x 220Ω Current-limiting resistors
* **Simulation Workspace:** Tinkercad Circuits platform

## Core Controller Logic
The C++ system model isolates individual lanes and executes synchronized delays:
* **Active Greens:** Ensures exactly one dynamic terminal direction holds transit clearance (High) while clamping crossway approaches to safe stop states (Red).
* **Intermediate Oranges:** Triggers a 3000ms warning threshold buffer to seamlessly cycle directional traffic handoffs without overlap hazards.

## Engineering Team & Credits
This firmware and simulated prototype were engineered collaboratively by our university project group:
* **Alina Zahra** (Group Leader)
* **Warda Batool**
* **Saniah Malik**
* **Javeria Ismail**
