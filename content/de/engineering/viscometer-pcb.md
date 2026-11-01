---
title: Steuerplatine für ein Viskosimeter
description: Altium-Designer-Leiterplatte für ein Viskosimeter mit zwei ESP32 (in Arbeit).
tags:
- leiterplatte
- altium
- esp32
- messtechnik
weight: 4
---

Entwurf einer einzelnen Platine in **Altium Designer** für ein Viskosimeter mit **zwei ESP32**-Modulen (WROOM-32, 38 Pins). Der zweite ESP32 steuert einen Wasserdosierer und ein Farb-Etikett mit TCS230.

### Entwurfsentscheidung
Eine Platine trägt beide ESP32-Module. Alle anderen Module (DRV8825, X9C103, TCS230, LCD und D4184) sind fertige Platinen, sodass keine einzelnen Bauteile gelötet werden müssen.
