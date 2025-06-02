---
title: "Interactive Laser Harp"
date: 2024-01-01
description: Musical harp using laser diodes and photodetectors to trigger notes by interrupting light beams. Developed with Arduino on a custom curved frame.
menu:
  sidebar:
    name: Laser Harp
    identifier: music-laser-harp
    parent: projects
    weight: 37
hero: images/1.png
tags:
  - Arduino
  - Sensors
  - Music
  - Laser
  - Embedded Systems
categories:
  - Interactive Systems
---

## Overview

This project consists of a laser harp, an interactive musical instrument that generates sound when a user interrupts visible laser beams with their hand. Each laser beam corresponds to a musical note. When the beam is blocked, the system detects the change and activates a tone through a built-in speaker.

The device is built on a curved wooden and plastic frame with multiple red laser diodes aligned with photodetectors (photodiodes). An Arduino microcontroller continuously reads each sensor and triggers a specific tone based on which beam was interrupted. A rotary selector allows the user to switch between rhythm or tone modes.

## How It Works

Each laser diode is aligned with a corresponding photodiode. When the beam reaches the sensor, the voltage level remains stable. When a hand blocks the beam, the Arduino detects the voltage drop and activates the sound associated with that position. The tones are generated programmatically within the Arduino.

## Main Features

- Sound triggering via visible laser beam interruption  
- Use of red laser diodes and aligned photodiodes  
- Arduino-controlled tone generation  
- Mode selection using rotary knob  
- Integrated speaker for audio output  

## Gallery

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px;">
  <img src="images/1.png" alt="Laser Harp - Front View">
  <img src="images/2.jpeg" alt="Laser Harp - Side View" style="width: 300px; height: 500px; object-fit: cover;">
</div>
