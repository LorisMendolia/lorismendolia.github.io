---
layout: page
title: Neuroutier
description: An analog neuromorphic processor architecture with dual synaptic and neuromodulatory crossbar array
img: assets/img/neuroutier.png
importance: 1
# category: work
related_publications: false
---

My latest chip Neuroutier produced its first spikes during the CapoCaccia Workshop in May 2026. Stay tuned for more exciting results and publications in the next months!

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neuroutier_ccwn.jpg" title="Neuroutier at CapoCaccia" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/co-activated hco.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
        <div class="caption">
            These two neurons are in mutual inhibition, but neuromodulate each other from spiking to bursting. When either neuron is stimulated alone, it produces tonic spiking. When both neurons are stimulated together, they neuromodulate each other to produce bursting activity, and form a half-center oscillator.
        </div> 
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/nmd releases inhibition.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %} 
        <div class="caption">
            The orange neuron is tonically spiking, and inhibits the blue neuron. When the orange neuron is neuromodulated to bursting, the blue neuron is released from inhibition during the inter-burst intervals, and is able to start spiking.
        </div> 
    </div>
</div>

This is the power of neuromodulation: the same network of neurons can produce radically different behaviors depending on the local or global neuromodulatory context.
