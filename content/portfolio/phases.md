+++
author = "Roy Jara"
title = "Phases"
date = "2019-03-05"
description = "ML Tracking + Image synthesis Installation."
tags = [
    "portfolio",
    "machine learning",
    "art",
]
categories = [
    "art",
    "newmedia",
]
series = ["Portfolio"]
imagelink = "images/backgrounds/phases_matrix_s.png"
+++

### ML in the arts final project @ UCSD (circa March 2019)

<br>

<p style='text-align: center; font-weight: bold; font-style: italic;'> <b>How do you make art with machine learning? </b></p>

To answer that we would need to rewind a little and first answer the age old question: 

<p style='text-align: center; font-weight: bold; font-style: italic;'> <b>What is art? </b></p>

Unfortunately, there is no definite answer. 

<p style='text-align: center; font-weight: bold; font-style: italic;'> <b>So... can anything be art? </b></p>

To avoid getting into a philosophical discussion, let's take art to be "a means of creative expression to convey ideas, emotions or messages."


<br>

---

<br>

### The goal for Phases

Create a new medium for creative expression using machine learning. Instead of making an artwork, we chose to make a tool that allows a new form of expression. Instead of using a hand to control the pencil traces on paper, we're using a hand to control the synthesis of a face. 

#### Main components:
- Low cost body tracking: CMU's Openpose
- Image synthesis: Nvidia's StyleGAN

#### Technical idea:

Presynthesize images to get a latent space of faces. Parameters to tune this space would be mainly the seeds (faces to interpolate) and the grid size.

 <img src="/images/phases/phases_matrix_s.png" alt="latent space example" width="100%"> 

Then we take the readings from the digital skeleton obtained from openpose to map movement from the skeleton to the latent space.

At the time, we were restricted on time and hardware so we had to stitch the two parts together - in other words, it wasn't running in realtime. 

I'll probably try to get it to run in realtime at some point. But for now, enjoy the side to side results (from 2019)!

{{< vimeo 341742466 >}}
{{< vimeo 341745596 >}}


<br>

---

<br>

### Shouts out to...

My project partner [@e_li_ot_](https://www.instagram.com/e_li_ot_/) <br>
And our wonderful instructor [Robert Twomey](https://roberttwomey.com/)