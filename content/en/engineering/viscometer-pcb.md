---
title: Viscometer Control Board
description: Altium Designer PCB for a viscometer built around two ESP32 boards (in progress).
tags:
- pcb
- altium
- esp32
- instrumentation
weight: 4
---

Design in **Altium Designer** of a single board for a viscometer with **two ESP32** modules (WROOM-32, 38-pin). The second ESP32 handles a water doser and a TCS230 color tag.

### Design decision
One board carries both ESP32 modules. All other modules (DRV8825, X9C103, TCS230, LCD and D4184) are ready-made boards, so no component-level soldering is needed.
