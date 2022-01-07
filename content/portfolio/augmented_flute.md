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
imagelink = "images/backgrounds/ligh_wip_bg.png"
+++

##### Why play a regular old flute when you can augment it using computers?

_An exploration for thc212 research presentation_

We all know and treasure the flute: the physics of resonating sound waves inside of the chamber, how daunting all the keys look to the inexperienced player, and how it is still used in modern music. The sound from the flute strongly approximates pure sine waves, yet the sound can be as expressive as the player desires via blowing modulations and lip placement.

However, I'm seeking to take this a step further and create interactions with software via hardware. Real-time sound effects are the first thing that comes to mind. So I'll start with that. But I picture this project becoming a modular platform that could enable further interaction (synthesis of computer graphics, automated accompaniment, sentiment detection, etc).
For now, let's start with the basics.

Real-time DSP - Bill of Materials:

- Flute
- USB-C Lapel Microphone
- Computer with Max/MSP
- Arduino Nano Sense 33 BLE
- 3D printed bracket
- ANT HR Monitor
- Display (projector, screen, LED Wall)

For the sake of simplicity and to get this project going with minimum cost, I'm using a cheap USB-C lapel mic (aprox $10 on ebay) connected to my macbook pro running max/msp.
The arduino's internal IMU will serve as a controller for any audio effects.
The ANT HR Monitor will be transmitting the player's heart rate to the arduino. The arduino will then retransmit the HR and the IMU data to the computer for control of parameters in max/msp or any other software to be used.
I'm thinking the HR could be used to create a drum beat based on that tempo.

The initial patches:

- Note detection
- Delay
- Reverb
- Looper

In order to get this prototype working fast, I'm going to be using existent functions/algorithms for the reverb and delay.

Later on:

- wekinator
