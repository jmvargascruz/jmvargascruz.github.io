---
title: "Sensor Module | USB HID Interface"
summary: "Modular sensor input system for driving simulators, designed with Arduino Pro Micro and RJ interfaces."
date: 2024-01-01
weight: 1
image: "/images/sections/projects/SensorModule/1.png"
logo: "/images/sections/projects/SensorModule/1.png"
tags: ["arduino", "embedded-systems", "microcontrollers", "electronics"]
repo: ""
external_link: ""
draft: false
showInProjects: true
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

{{< img src="/images/sections/projects/SensorModule/top.png" title="Top View" align="center" height="300" >}}
{{< img src="/images/sections/projects/SensorModule/angled.png" title="Angled View" align="center" height="300" >}}
{{< img src="/images/sections/projects/SensorModule/final.png" title="Final Assembly & Wiring" align="center" height="300" >}}
{{< img src="/images/sections/projects/SensorModule/pcb.png" title="PCB Layout" align="center" height="300" >}}

## Notes

This module was designed as part of a driving simulator system for training and evaluation purposes. It is compatible with USB-HID input systems and simplifies hardware interfacing through RJ modular connections.
