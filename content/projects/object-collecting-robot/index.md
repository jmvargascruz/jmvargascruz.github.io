---
title: "Object Collecting Robot | Simulation and Control with SolidWorks and LabVIEW"
date: 2024-01-01
description: Autonomous robot simulated in LabVIEW with 3D environment in SolidWorks for object collection tasks.
menu:
  sidebar:
    name: Object Collecting Robot
    identifier: object-collecting-robot
    parent: projects
    weight: 40
hero: images/1.png
tags:
  - Robotics
  - Simulation
  - Control
categories:
  - Robotics
---

## Overview

This project consisted in designing, programming, and simulating a virtual cleaning robot in a LabVIEW environment. The robot was tasked with autonomously navigating a predefined arena, identifying and collecting cans, and returning to the container zone without colliding with obstacles. The simulation included interaction with a 3D model built in SolidWorks, where the robot movements from LabVIEW were reflected in real time.

## System Behavior

- The robot starts at a fixed home position  
- It moves one tile at a time in X and/or Y direction (no rotation)  
- Obstacles (3) and cans (8) are randomly placed in a 20x20 arena  
- When a can is detected from one of its four corners, the turret aligns to a contact angle (45º, 135º, 225º, 315º) to simulate grasping  
- The robot dynamically maps obstacles to avoid them  
- Once all cans are collected, the robot must return to the container area within 4 minutes  

## Mathematical Logic

- Robot movement follows coordinate-based logic, not continuous time  
- Discrete movement:  
  \[
  (x, y)_{t+1} = (x, y)_t + \Delta x, \Delta y \quad \text{where } \Delta x, \Delta y \in \{-1, 0, 1\}, |\Delta x| + |\Delta y| \leq 1
  \]  
- Turret orientation is selected by conditional quadrant logic  
- Basic pathfinding implemented with coordinate validation and memory of visited positions  

## Tools and Technologies

- **LabVIEW**: Main logic engine for control flow, decision-making, and user interface  
- **SolidWorks**: 3D CAD modeling of the robot and simulation environment  
- **Real-Time Integration**: Robot movements and control signals generated in LabVIEW were executed in real time within the SolidWorks simulation.

## Achievements

- Completed the full simulation successfully in under four minutes  
- Demonstrated autonomous behavior with obstacle avoidance and object retrieval  
- Complete LabVIEW documentation and state-based control design  

## Video
{{< youtube Qzy49-ygo1U >}}
