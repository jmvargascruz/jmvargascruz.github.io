---
title: "Gripper Design for Tomato Harvesting"
date: 2024-01-01
description: End-effector subsystem for a robotic tomato harvesting system, integrating sensors and actuators with Arduino control.
menu:
  sidebar:
    name: Gripper Design
    identifier: gripper-design
    parent: projects
    weight: 42
hero: images/7.jpeg
tags:
  - Arduino
  - Embedded Systems
  - Robotics
  - 3D Printing
  - Actuators
categories:
  - Robotics
---

## Overview

This project was part of an international university challenge focused on autonomous tomato harvesting, conducted in collaboration with Mondragon Unibertsitatea and Tecnológico de Monterrey. The main contribution involved designing and building a functional gripper prototype for the robotic system.

The end-effector was developed using 3D-printed components and included an integrated stepper motor, limit switch, and potentiometer. The control system was implemented on an Arduino UNO, which managed the opening and closing of the gripper based on sensor inputs.

## System Integration

The gripper was mounted on a UR10 collaborative robot programmed to follow a predefined trajectory. The system was validated by successfully picking a tomato and placing it in a container.

## Main Features

- 3D-printed mechanical gripper
- Stepper motor for actuation
- Potentiometer for position feedback
- Limit switch for motion limits
- Arduino-based embedded control
- UR10e robotic arm integration

## Technologies Used

- SolidWorks for 3D design  
- Arduino UNO for stepper motor control  
- UR10e for robot motion execution  
- Manual wiring and prototyping tools  

## Gallery

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 10px;">
  <img src="images/2.png" alt="2">
  <img src="images/1.png" alt="1">
  <img src="images/3.png" alt="3">
  <img src="images/4.jpeg" alt="4">
  <img src="images/5.jpeg" alt="5">
  <img src="images/6.jpeg" alt="6">
  <img src="images/7.jpeg" alt="7">

</div>
