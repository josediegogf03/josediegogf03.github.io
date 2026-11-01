---
title: Scheda di controllo per viscosimetro
description: PCB in Altium Designer per un viscosimetro basato su due ESP32 (in corso).
tags:
- pcb
- altium
- esp32
- strumentazione
weight: 4
---

Progettazione in **Altium Designer** di un'unica scheda per un viscosimetro con **due ESP32** (WROOM-32, 38 pin). La seconda ESP32 gestisce un dosatore d'acqua e un'etichetta colore con TCS230.

### Scelta progettuale
Una sola scheda ospita le due ESP32. Gli altri moduli (DRV8825, X9C103, TCS230, LCD e D4184) sono schede già pronte, quindi non si saldano componenti singoli.
