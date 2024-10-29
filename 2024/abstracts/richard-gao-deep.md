# Deep inverse modeling reveals dynamic-dependent invariances in neural circuit mechanisms

**Authors:** Richard Gao, Michael Deistler, Auguste Schulz, Pedro J. Gonçalves, Jakob H. Macke
                           


**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Neural population dynamics are shaped by many cellular, synaptic, and network properties. Not only is it important to understand how coordinated changes in circuit parameters alter neural activity, but also when dynamics are unaffected by—or invariant to—such changes. Computational modeling has revealed invariances in single neurons and small circuits that are thought to reflect their robustness against variability and perturbations. However, generalizing these insights to larger circuits in cortex and other brain areas remains challenging. A key bottleneck lies in inverse modeling of neural circuits with spiking network models, i.e., identifying parameter configurations that quantitatively match dynamics observed in neural recordings. Here, we present Automated Model Inference from Neural Dynamics (AutoMIND) for efficient discovery of invariant circuit model configurations. AutoMIND leverages a mechanistic model with adaptive spiking neurons and clustered connectivity, which displays a rich variety of spatiotemporal dynamics. Probabilistic deep generative models—trained on network simulations only—then returns many parameter configurations consistent with a given target observation of neural activity. Applied to several datasets, AutoMIND discovers circuit models of synchronous network bursting in human brain organoids across early development, as well as models capturing complex frequency profiles of Neuropixels recordings in mouse hippocampus and cortex. In each case, we obtain hundreds of configurations that compose a (nonlinear) parameter subspace in which population dynamics remain unchanged. Surprisingly, global and local geometries of the invariant subspace are not fixed, but differ for different dynamics. Together, our results shed light on dynamic-dependent invariances of circuit parameters underlying diverse population dynamics, while demonstrating the flexibility of AutoMIND for inverse modeling of neural circuits.

