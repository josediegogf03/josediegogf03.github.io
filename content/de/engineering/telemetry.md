---
title: Echtzeit-Telemetriesystem
description: Datenerfassung und Telemetrie für ein energieeffizientes Elektrofahrzeug (Shell Eco-marathon).
tags:
- telemetrie
- eingebettete-systeme
- altium
- esp32
weight: 1
---

Telemetriesystem für das Fahrzeug von **EcoVolt CCM**. Es erfasst und analysiert Fahrzeugdaten in Echtzeit, um den Energieverbrauch während des Rennens zu optimieren.

### Was es misst
- GPS-Position und Geschwindigkeit
- Beschleunigungssensor und Gyroskop
- Strom- und Spannungssensoren
- Hall-Sensoren für Geschwindigkeit und Gas-/Bremseingaben

### Hardware und Ansatz
- **4 Leiterplatten**, mitentwickelt in **Altium Designer**: 3 Telemetrie-Platinen (eine mit Energiereserve) und 1 Hall-Sensor-Platine für den Motor
- ESP32-basierte Telemetrie mit Vorhersagemodellen und maschineller Analyse in der Cloud

### Ergebnisse
- **Data & Telemetry Award** beim Shell Eco-Marathon Americas: Sieger 2025, Zweiter 2026
- Bei **IEEE SAIBOT 2026** eingereichter Artikel: *Real-Time Telemetry and Computational Intelligence Pipeline for Energy-Efficient Driving of an Electric Eco-Marathon Vehicle*
