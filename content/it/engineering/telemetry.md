---
title: Sistema di telemetria in tempo reale
description: Acquisizione dati e telemetria per un veicolo elettrico ad alta efficienza energetica (Shell Eco-marathon).
tags:
- telemetria
- sistemi-embedded
- altium
- esp32
weight: 1
---

Sistema di telemetria del veicolo di **EcoVolt CCM**. Raccoglie e analizza i dati del veicolo in tempo reale per aiutare a ottimizzare il consumo di energia durante la gara.

### Cosa misura
- Posizione e velocità via GPS
- Accelerometro e giroscopio
- Sensori di corrente e tensione
- Sensori Hall per velocità e comandi di acceleratore/freno

### Hardware e approccio
- **4 PCB** co-progettate in **Altium Designer**: 3 schede di telemetria (una con riserva di energia) e 1 scheda di sensori Hall per il motore
- Telemetria basata su ESP32 con modelli predittivi e analisi di machine learning nel cloud

### Risultati
- **Data & Telemetry Award** allo Shell Eco-Marathon Americas: vincitore nel 2025, secondo nel 2026
- Articolo inviato a **IEEE SAIBOT 2026**: *Real-Time Telemetry and Computational Intelligence Pipeline for Energy-Efficient Driving of an Electric Eco-Marathon Vehicle*
