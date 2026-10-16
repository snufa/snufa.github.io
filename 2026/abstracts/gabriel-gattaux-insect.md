# Insect Neural Mechanisms of Navigation Through Robotics

**Authors:** Gabriel Gattaux
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Neuromorphic engineering is not dead; it has specialized. The silicon retina illustrates how progress emerges when neural principles are studied together with the physical problem they solve: acquiring and transforming visual information through an embodied sensor. Neuromorphic navigation poses a similar systems-level challenge: before selecting neuronal dynamics for implementation in silicon, we must identify the population-level architecture that transforms spatial information into behaviour. In that vein, I designed computational models of insect neural circuits by testing their ability to generate visual homing and route-following behaviour in embodied robots.

Insects provide a compelling model: ants and bees navigate over enormous distances relative to their body size using milligram-scale brains and low resolution vision. However, current knowledge remains fragmented: although the insect mushroom bodies and central complex are associated with visual memory and directional processing, respectively, it remains unclear how their population codes interact to transform learned views into steering commands. Moreover, these mechanisms remain largely absent from robotic navigation, where their use is confined to a handful of research prototypes.

To address this gap, I developed connectome-inspired architectures in which visual familiarity is associated with relevant directions and transformed into a heading-error signal shared by visual homing and route following. On a car-like robot, the model enabled one-shot route learning and continuous navigation over 1.6 km across 113 outdoor trials, with a median lateral error below 25 cm, using 800-pixel vision and approximately 500 mW on a Raspberry Pi. Transfer to a 33 g micro-drone demonstrated route return and landing from 24 × 24-pixel images. The memory storage needed was less than 4 kB. Ongoing humanoid experiments showed similar prowess.

These results provide a closed-loop test of how visual memory and directional representations may interact in insect navigation, while identifying population-level computational building blocks that future neuromorphic implementations must preserve.