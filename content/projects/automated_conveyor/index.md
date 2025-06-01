---
title: "Automated Conveyor System with Metal Detection and Bag Sealing Integration | PLC S1200"
date: 2024-01-01
description: Modular sensor input system for driving simulators, designed with Arduino Pro Micro and RJ45 connectors.
menu:
  sidebar:
    name: Automated Conveyor
    identifier: automated_conveyor
    parent: projects
    weight: 22
hero: images/1.png
tags:
  - Arduino
  - Embedded Systems
  - Microcontrollers
  - Electronics
categories:
  - Robotics
---

## Overview

This module connects sensors from a driving simulator using RJ45 Keystone jacks and custom wiring. It includes signals such as blinkers, gear selector, handbrake, seatbelt, and ignition. Each sensor is mapped to a virtual joystick button through a USB HID interface.

The firmware handles input logic and emulates a USB joystick using the Joystick.h library. The module is housed in a 3D-printed case and has a custom PCB prepared for future versions.

## Key Features

- Plug-and-play sensors via RJ45 connectors  
- Arduino Pro Micro with custom firmware  
- Logical handling of multiple inputs  
- 3D printed enclosure, PCB-ready for future upgrade  
- Real-time USB joystick mapping.

## Technologies Used

- 3D CAD (SolidWorks)  
- PCB design (KiCad)  
- Arduino C++  
- Joystick.h HID library  
- 3D printing  

## Gallery

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px;">
  <img src="images/top.png" alt="Top View">
  <img src="images/angled.png" alt="Angled View">
  <img src="images/final.png" alt="Final Assembly">
  <img src="images/pcb.png" alt="PCB Layout">
  <img src="images/module.png" alt="Module">
  <img src="images/pcb_design_1.png" alt="PCB">
  <img src="images/module2.png" alt="module">
  <img src="images/pcb_design_2.png" alt="PCB 2">
  <img src="images/module_N.png" alt="module_N">
</div>
