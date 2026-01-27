---
youtube: ucL5AvmdD1E?si=HoubevvZefGur1Vg&start=1124
---
# Energy-Based and Transformer Models for Neural Circuit Modeling

**Authors:** Abolfazl HaqiqiFar, Reza Jafari
                           


**Presentation type:** Flash talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Large language models (LLMs) such as GPT-4 have shown strong performance in handling text. They rely on probability distributions over discrete tokens, which makes them powerful for language but not well-suited for continuous, high-dimensional signals such as those recorded from neural circuits. Neural data is dynamic and multimodal, and representing it with token-based models loses important uncertainty and temporal structure.
Energy-Based Models (EBMs) offer an alternative. Instead of predicting tokens, EBMs assign energy values to possible outputs and search for states that minimize energy. This allows them to model multimodal and continuous data more flexibly. Hopfield networks and Boltzmann machines are early examples. Recent work suggests that EBMs, trained with regularized or self-supervised objectives, could better capture neural circuit activity.
However, a computational model alone is not enough. To understand and predict real brain function, models must also reflect biological motifs and architectures. Core circuit motifs—such as feedforward and feedback connections, recurrent loops, and lateral inhibition—are the building blocks of neuronal computation. Larger-scale strategies like topographic mapping and dimensionality expansion show how these motifs combine to support perception, decision-making, and motor control. Mapping AI mechanisms, such as attention in transformers or attractor dynamics in EBMs, to these biological structures provides a pathway for integration.
This work argues that combining EBMs with biological principles can create computationally powerful and biologically plausible models. Such models would not only capture surface-level patterns in data but also offer insight into the mechanisms that underlie neural circuits. This approach brings us closer to bridging machine learning with systems neuroscience.