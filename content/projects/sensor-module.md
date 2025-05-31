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

The module supports the following inputs:

- Gear lever (position detection)
- Turn signals (left/right indicators)
- Ignition switch (start button)
- Seatbelt sensor
- Parking brake sensor
- Directional indicator control
- Extra digital Input/Output connectors

## Technologies Used

- **Microcontroller**: Arduino Pro Micro (ATmega32U4)
- **Design tools**: KiCad, SolidWorks
- **Connection standard**: RJ interfaces for modular sensor inputs
- **USB Interface**: HID profile to be recognized as a joystick/controller

## 🖼️ Gallery

Here is a visual overview of the design and implementation process:

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 10px;">
    <img src="/images/sections/projects/SensorModule/top.png" alt="Top View">
    <img src="/images/sections/projects/SensorModule/angled.png" alt="Angled View">
    <img src="/images/sections/projects/SensorModule/final.png" alt="Final Assembly & Wiring">
    <img src="/images/sections/projects/SensorModule/pcb.png" alt="PCB Layout">
</div>

## 📝 Notes

This module was used in a project of a driving simulator used to assess drivers and issue driving licences tests.
