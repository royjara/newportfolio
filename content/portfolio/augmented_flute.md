+++
author = "Roy Jara"
title = "Augmented Flute"
date = "2021-10-23"
description = "Musical instrument for new media performances."
tags = [
    "portfolio",
    "arduino",
    "maxmsp",
]
categories = [
    "music",
    "newmedia",
]
series = ["Portfolio"]
imagelink = "images/backgrounds/inverted_curves.png"
+++

<h4> <strong>Why play a regular flute when you can augment it using computers?</strong></h4>

An exploration for __UCLA Theater C212: Emerging Technologies for Live Performance__

We all know and treasure the flute: the physics of resonating sound waves inside of the chamber, how daunting all the keys look to the inexperienced player, and how it is still used in modern music. The sound from the flute strongly approximates pure sine waves, yet the sound can be as expressive as the player desires via blowing modulations and lip placement.

However, I'm seeking to take this a step further and create interactions with software via extra input sensors. Modulation of real-time sound effects are the first thing that comes to mind. So I'll start with that. But I picture this project becoming a modular platform that could enable further interaction (synthesis of computer graphics, automated accompaniment, sentiment detection, etc).
For now, let's start with the basics.

<br>

---
<br>

Bill of Materials:

- Flute
- Arduino Nano Sense 33 BLE (~$30)
- USB-C Lapel Microphone (~$8)
- Computer with Max/MSP
- ANT HR Monitor
- Display (projector, screen, LED wall, etc)
- 3D printed bracket


### Wiring diagram: ###

![wiringdiagram](/images/augmented_flute/wiring_iteration1.png)

For the first iteration, I'm just seeking connectivity between the different parts. Later, we can use the physical parts+connections to design fuller systems with custom DSP/graphics.


## Next steps...

- implementation #1
- wekinator
