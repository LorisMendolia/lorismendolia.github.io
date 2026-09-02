---
layout: page
title: A neuromodulable CMOS neuron
description: A subthreshold current-mode neuron capable of neuromodulation
img: assets/img/pcb1.png
importance: 1
# category: work
related_publications: true
---

This project presents the first integrated circuit I designed during my PhD: an analog silicon neuron implemented in a 180 nm CMOS technology.

The neuron operates in the subthreshold regime, reproducing biologically-inspired spiking dynamics with extremely low energy consumption. Its main innovation is the addition of **neuromodulation**, allowing its behavior to be continuously tuned through dedicated analog control signals. This makes it possible to adapt the neuron's dynamics in real time without modifying the circuit itself.

The design combines compactness, configurability, and biological realism, and served as the foundation for much of my subsequent work on adaptive and reliable neuromorphic hardware.

{% include video.liquid path="assets/video/chip1_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} 

### This page is under construction. More details and results will be added soon. In the meantime, you can check out the related publication  {% cite mendolia_neuromodulable_2025 %}