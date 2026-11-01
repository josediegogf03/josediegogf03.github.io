---
title: Sistema de telemetría en tiempo real
description: Adquisición de datos y telemetría para un vehículo eléctrico de alta eficiencia (Shell Eco-marathon).
tags:
- telemetría
- sistemas-embebidos
- altium
- esp32
weight: 1
---

Sistema de telemetría del vehículo de **EcoVolt CCM**. Recolecta y analiza datos del vehículo en tiempo real para ayudar a optimizar el consumo de energía durante la carrera.

### Qué mide
- Posición y velocidad por GPS
- Acelerómetro y giroscopio
- Sensores de corriente y voltaje
- Sensores Hall para velocidad y entradas de acelerador/freno

### Hardware y enfoque
- **4 PCB** co-diseñadas en **Altium Designer**: 3 placas de telemetría (una con reserva de energía) y 1 placa de sensores Hall para el motor
- Telemetría basada en ESP32 con modelos predictivos y análisis de aprendizaje automático en la nube

### Resultados
- **Data & Telemetry Award** en Shell Eco-Marathon Americas: ganador en 2025, subcampeón en 2026
- Artículo enviado a **IEEE SAIBOT 2026**: *Real-Time Telemetry and Computational Intelligence Pipeline for Energy-Efficient Driving of an Electric Eco-Marathon Vehicle*
