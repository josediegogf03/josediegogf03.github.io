---
title: Carte de commande de viscosimètre
description: PCB sous Altium Designer pour un viscosimètre construit autour de deux ESP32 (en cours).
tags:
- pcb
- altium
- esp32
- instrumentation
weight: 4
---

Conception sous **Altium Designer** d'une carte unique pour un viscosimètre avec **deux ESP32** (WROOM-32, 38 broches). La seconde ESP32 gère un doseur d'eau et une étiquette de couleur avec un TCS230.

### Choix de conception
Une seule carte porte les deux ESP32. Les autres modules (DRV8825, X9C103, TCS230, écran LCD et D4184) sont des cartes toutes faites ; aucun composant n'est donc soudé individuellement.
