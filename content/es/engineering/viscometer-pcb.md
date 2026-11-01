---
title: Placa de control para viscosímetro
description: PCB en Altium Designer para un viscosímetro con dos ESP32 (en curso).
tags:
- pcb
- altium
- esp32
- instrumentación
weight: 4
---

Diseño en **Altium Designer** de una sola placa para un viscosímetro con **dos ESP32** (WROOM-32, 38 pines). La segunda ESP32 se encarga de un dosificador de agua y una etiqueta de color con TCS230.

### Decisión de diseño
Una sola placa lleva las dos ESP32. Los demás módulos (DRV8825, X9C103, TCS230, LCD y D4184) son placas ya hechas, por lo que no se sueldan componentes individuales.
