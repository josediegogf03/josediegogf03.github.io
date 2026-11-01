---
title: Real-Time Telemetry System
description: Data acquisition and telemetry for an energy-efficient electric vehicle (Shell Eco-marathon).
tags:
- telemetry
- embedded-systems
- altium
- esp32
weight: 1
---

Telemetry system for the **EcoVolt CCM** vehicle. It collects and analyzes vehicle data in real time to help optimize energy consumption during the race.

### What it measures
- GPS position and speed
- Accelerometer and gyroscope
- Current and voltage sensors
- Hall sensors for speed and throttle/brake inputs

### Hardware and approach
- **4 PCBs** co-designed in **Altium Designer**: 3 telemetry boards (one with an energy reserve) and 1 Hall-sensor board for the motor
- ESP32-based telemetry with predictive models and cloud machine-learning analysis

### Results
- **Data & Telemetry Award** at Shell Eco-Marathon Americas: winner in 2025, runner-up in 2026
- Paper submitted to **IEEE SAIBOT 2026**: *Real-Time Telemetry and Computational Intelligence Pipeline for Energy-Efficient Driving of an Electric Eco-Marathon Vehicle*
