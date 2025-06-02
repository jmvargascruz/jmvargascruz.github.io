---
title: "Automated Conveyor | Siemens S1200 PLC"
date: 2024-01-01
description: Fully automated conveyor belt project using Siemens S1200 PLC and TIA Portal for real-time item inspection, rejection, counting, and packaging logic.
menu:
  sidebar:
    name: Automated Conveyor
    identifier: automated-conveyor
    parent: projects
    weight: 22
hero: images/1.jpg
tags:
  - PLC
  - Ladder Logic
  - TIA Portal
  - Automation
  - Mechatronics
categories:
  - Industrial Automation
---

## Overview

This project consists of an automated conveyor system programmed in ladder logic using Siemens TIA Portal. The system handles item inspection, grouping, and packaging. It is designed to reject metallic contaminants, count valid items, and seal them into bags as part of a defined automation cycle.

## System Behavior

- A start button activates the conveyor.
- Items are placed on the belt at a fixed rate of 1 per second.
- A metal sensor checks each item:
  - If metal is detected, a pneumatic actuator ejects it.
  - Non-metallic items continue and are counted.
- After five valid items are collected:
  - A heat-sealing actuator seals the bag.
  - A second actuator ejects the sealed bag and triggers a sound alert.
- The system pauses until a new bag is placed and the resume button is pressed.
- After three bags are sealed, the system stops automatically.

## Tools and Technologies

- **Software:** TIA Portal, Siemens Ladder Logic  
- **PLC:** Siemens S7-1200 PLC (simulated)  
- **Actuators:** Pneumatic actuators, heat sealer  
- **Sensors:** Inductive proximity sensor for metal detection

## Video

{{< youtube bgzaS4JFpUc >}}
