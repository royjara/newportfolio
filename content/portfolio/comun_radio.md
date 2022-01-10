+++
author = ["Roy Jara"]
title = "comun.radio"
date = "2021-04-30"
description = "Peru community radio."
tags = [
    "portfolio",
    "cloud",
    "music",
]
categories = [
    "music",
    "radio",
]
series = ["Portfolio"]
imagelink = "/images/comunradio/comunradio1.png"
+++

### Some context

> [__comun.radio__](///comun.radio) was created as a response to the lack of distribution opportunities for the forward thinking musicians and sound artists in Peru.

 <img src="/images/comunradio/comunradio1.png" alt="dj booth" width="100%"> 

Peru is a country gifted with an extraordinary diversity of people, races, languages and customs. With so much potential for richness within modern artistic practices, this is unfortunately for from the reality. Focusing on music, the predominant radio outlets for distribution of modern music are hesitant to look to Peruvians and Peruvian traditions. Local radio stations within the different regions of Peru do stream traditional music, but the radios with national coverage prefer to abroad for music. But most importantly, there is no one unified radio that seeks to challenge genre divisions and instead curate music for its actual artistic value, regardless of time period, origin, language, or genre.

Diana Taylor, in her book Archive in the Repertoire, describes the artistic environment in Peru for theatrical works that seek to embody our history, our traditions, and our culture. This environment prevails for practices beyond theatre, including visual arts, music, and performance.

> [Peru is] a country that pits nationality against ethnicity, literacy against orality, the archive against the repertoire of embodied knowledge. In Peru, the urban turns its back on the rural, and languages (Spanish, Quechua, and Aymara) serve more to differentiate among groups and silence voices than to enable communication. (Taylor 191)

[__comun.radio__](///comun.radio) was created as a response to the lack of distribution opportunities for forward thinking musicians and sound artists in Peru. Even though this is still an evolving project, we are continuously working towards becoming the platform that will renew the appreciation for Peruvian music, and the outlet that will provide more opportunities to overlooked and underrepresented musicians.

<br>

---

<br>

### Tech stack

The cloud computing paradigm empowers the small entrepreneur and provides them with the tools needed to avoid upfront costs of purchasing hardware. Via cloud computing, we can use infrastructure that will grow as our platform grows in popularity and complexity.

For the people that are seeking to create an internet radio, I'll list some of the essential technologies that we've used to build __comun.radio__.

#### [Digital Ocean](https://www.digitalocean.com/)

DO is a relatively small cloud provider compared to the big companies around. Nevertheless, this platform was ideal for our needs because it offers the highest network bandwidth per dollar. Therefore, this helps us reduce our streaming costs without sacrificing quality.

Currently we're using a simple auto-scaling group architecture as our initial solution. Due to the relatively low cost of this implementation, we're in no desperate need to further optimize the architecture. However, as technologies continue to roll out, we will evaluate and implement changes accordingly.

 <img src="/images/comunradio/do_1.png" alt="cloud architecture solution" width="100%"> 


#### [Azuracast](https://www.azuracast.com/)

This open-source radio platform aggregates multiple radio technologies (the most important being liquidsoap and icecast). This solution includes graphical interfaces for easy management, content management, and an array of multiple features and configurations that are quite good. This project hasn't reached an official 1.0 release yet, but it is surprisingly stable and has a highly dedicated community.

#### [BUTT](https://danielnoethen.de/butt/)

BUTT (Broadcast Using This Tool) is a lifesaver. Open source software comes in handy once again. BUTT is a small but sturdy tool to broadcast remotely. It integrates connects to Icecast streams running inside of Azuracast to then relay the content to the listeners.

#### [Readymag](https://readymag.com/)

Russian no-code platform for making visually pleasing websites. No-code platforms are the future. Although we might migrate soon, the UI is highly intuitive and minimal, which is ideal for people who are just getting started. RM's community is extremely helpful too.

<br>

---

<br>

> If you any further inquiries don't hesitate to contact me! - see about for email or footer for ig

### Huge thanks to the people that are helping to build this radio:
- [@sebastiangalliani](https://www.instagram.com/sebastiangalliani/)
- [@unjust.systems](https://www.instagram.com/unjust.systems/)