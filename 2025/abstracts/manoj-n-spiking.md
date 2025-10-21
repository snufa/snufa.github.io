# Spiking Differential Equation Solvers: A Minimal Framework for Dynamical Computation

**Authors:** Manoj N H, Avisha Mathur, Aryan Jain, Keshav Garodia, Veeranatesan S
                           


**Presentation type:** Talk at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking neural networks (SNNs) are increasingly recognized as universal function approximators, yet most demonstrations focus on static mappings rather than dynamical systems. Many theories of cortical computation, however, including predictive coding, are naturally expressed as differential equations: neuronal states evolve to minimize prediction error over time. This raises a fundamental question: can spiking circuits directly approximate such dynamical systems in a biologically plausible and computationally useful way? 
We introduce a minimal framework for spiking differential equation solvers, where populations of spiking neurons approximate both the state variables and their derivatives. Preliminary results on canonical ODEs (e.g., exponential decay, damped oscillators) demonstrate that spiking leaky integrate-and-fire neuron networks can accurately reproduce solutions while maintaining biologically plausible constraints such as event-driven communication and local learning. This line of work highlights the potential of SNNs not only as models of cortical computation but also as neuromorphic solvers for dynamical systems, bridging theory, neuroscience, and engineering, offering a neuromorphic substrate for continuous-time computation.
