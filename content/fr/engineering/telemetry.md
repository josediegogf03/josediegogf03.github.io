---
title: Système de télémétrie en temps réel
description: Acquisition de données et télémétrie pour un véhicule électrique économe en énergie (Shell Eco-marathon).
tags:
- télémétrie
- systèmes-embarqués
- altium
- esp32
weight: 1
---

Système de télémétrie du véhicule d'**EcoVolt CCM**. Il collecte et analyse les données du véhicule en temps réel pour aider à optimiser la consommation d'énergie pendant la course.

### Ce qu'il mesure
- Position et vitesse par GPS
- Accéléromètre et gyroscope
- Capteurs de courant et de tension
- Capteurs à effet Hall pour la vitesse et les commandes d'accélérateur/frein

### Matériel et approche
- **4 PCB** co-conçus sous **Altium Designer** : 3 cartes de télémétrie (dont une avec réserve d'énergie) et 1 carte de capteurs Hall pour le moteur
- Télémétrie basée sur ESP32 avec modèles prédictifs et analyse par apprentissage automatique dans le cloud

### Résultats
- **Data & Telemetry Award** au Shell Eco-Marathon Americas : lauréat en 2025, finaliste en 2026
- Article soumis à **IEEE SAIBOT 2026** : *Real-Time Telemetry and Computational Intelligence Pipeline for Energy-Efficient Driving of an Electric Eco-Marathon Vehicle*
