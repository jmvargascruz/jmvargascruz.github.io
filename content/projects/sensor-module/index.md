---
title: "Sensor Module | USB HID Interface"
date: 2024-01-01
description: Modular sensor input system for driving simulators, designed with Arduino Pro Micro and RJ interfaces.
menu:
  sidebar:
    name: Sensor Module
    identifier: sensor-module
    parent: projects
    weight: 10
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

This project involved the design and implementation of a modular sensor interface for a driving simulator system. It was designed to replicate typical vehicle control inputs and interface them as a USB Human Interface Device (HID), enabling driver action monitoring in evaluation systems.

## Connected Sensors

- Gear lever (position detection)
- Turn signals (left/right indicators)
- Ignition switch (start button)
- Seatbelt sensor
- Parking brake sensor
- Directional indicator control

## Technologies Used

- **Microcontroller**: Arduino Pro Micro (ATmega32U4)
- **Design tools**: KiCad, SolidWorks
- **Connection standard**: RJ modular sensor inputs
- **USB Interface**: HID profile for joystick compatibility

## Gallery


{{< img src="images/top.png" title="Top View" align="center" width="300" >}}

{{< vs >}}

{{< img src="images/angled.png" title="Angled View" align="center" width="300" >}}

{{< vs >}}

{{< img src="images/final.png" title="Final Assembly" align="center" width="300" >}}

{{< vs >}}

{{< img src="images/pcb.png" title="PCB Layout" align="center" width="300" >}}



## Notes

This module was designed as part of a driving simulator system for training and evaluation purposes. It is compatible with USB-HID input systems and simplifies hardware interfacing through RJ modular connections.
