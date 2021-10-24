---
title: "COMUN RADIO"
date: 2019-12-23T20:56:42+06:00
type: portfolio
image: "images/projects/comunradio_square.png"
category: ["WEB RADIO"]
project_images: ["images/projects/comunradio1.png",
"images/projects/comunradio1.png",]
---

In a country where most radio stations only look for music overseas, a vaccuum for the promotion of national talent served as motivation to start Comun Radio, a community radio based in Lima, Peru.

> "Driven by musicians, intended for fellow music lovers."

##### Cloud Server: Digital Ocean + Azuracast

The cloud computing paradigm empowers the small entrepreneur and provides them with the tools needed to avoid upfront costs of purchasing hardware. Via cloud computing, we can easily create and destroy a server (or multiple when we need to scale) without having to actually own the machine. AWS, Google Cloud, Azure are the most popular options. But we're proud to be using Digital Ocean (DO).

Apart from the seamless installation of an azuracast instance, this cloud provider offers the best network throughput for the money.

Now, inside of this DO droplet, we're using Azuracast to handle the media ingestion as well as the programming and streaming.

##### DJ Clients: BUTT

BUTT (Broadcast Using This Tool) is a lifesaver. Open source software comes in handy once again. BUTT is a small but sturdy tool to broadcast remotely. It integrates effortlessly with the Azuracast system after some initial configuration.

##### Frontend: Readymag

Disclaimer: still a WIP

Upcoming work includes:

- Scripts for auto-editing audio and video.
- Scripts for automatically populating content (youtube, soundcloud)
- UX/UI improvements for a more cohesive navigation.
- Calendar and schedule views on the frontend.
