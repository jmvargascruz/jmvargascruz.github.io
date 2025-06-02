---
title: "Interactive Laser Harp"
date: 2024-01-01
description: Musical harp with red laser LED beam interruption to trigger notes. Designed with Arduino and photodetectors arranged on a curved frame.
menu:
  sidebar:
    name: Laser Harp
    identifier: music-laser-harp
    parent: projects
    weight: 32
hero: images/1.png
tags:
  - Arduino
  - Sensors
  - Music
  - Infrared
  - Embedded Systems
categories:
  - Interactive Systems
---

## Overview

This project is a laser harp, an electronic musical instrument that plays notes when the user interrupts RED laser light beams with their hand. Each beam represents one note. When a beam is blocked, a sensor detects the change and sends a signal to the Arduino to play the sound.

The system uses a curved structure with infrared emitters and photodiodes. An Arduino reads the sensors and generates sound using a small speaker. A knob lets the user change between rhythm or sound modes.

## How It Works

Each emitter is paired with a photodiode. When the light reaches the photodiode, the signal is stable. If a hand blocks the beam, the Arduino detects the change and plays a specific tone.

## Main Features

- Note triggering by blocking infrared beams  
- Sound generation using Arduino  
- Built-in speaker  
- Mode selector knob  

## Gallery

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 10px;">
  <img src="images/1.png" alt="Laser Harp - Full View">
</div>
