# Demonstrating Universal Approximation with a Biophysically Faithful Hodgkin–Huxley Engine

**Authors:** Nicholas Windley, Desmond Atkins 
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

The Spiking Neural Network Universal Function Approximation (SNUFA) theorem establishes that spiking neurons are not only biologically plausible but also computationally complete. Yet most demonstrations of SNUFA rely on simplified integrate-and-fire models or on high-performance computing resources, making the concept difficult to reproduce in classroom or laboratory settings. As a result, SNUFA often remains a theoretical result presented on slides rather than a principle students or researchers can interactively explore.

We present a new Engine that implements Hodgkin–Huxley (HH)-class neuron models with dendritic dynamics, neuromodulator-modulated plasticity, and hippocampal state persistence, while running efficiently on commodity CPUs. Benchmarking shows canonical HH spike fidelity against ODE solutions, validating the solver’s biological accuracy. Using this foundation, we demonstrate nonlinear function approximation and temporal pattern learning tasks—classic examples of SNUFA—achieved with biophysically faithful neurons in real time, without HPC overhead.

Unlike existing platforms such as NEURON, Brian2, or NEST, which typically require HPC clusters or simplify neural dynamics, our approach combines full HH-class fidelity with accessibility. This dual capability enables practical demonstrations of SNUFA that are both scientifically rigorous and easy to deploy in diverse research and teaching environments.

The Engine is accessed through BioSynapStudio, an integrated design environment that allows researchers, engineers, and educators to configure models, run experiments, and visualise results through an intuitive interface. We have packaged the SNUFA demonstrations into ready-to-use modules, lowering the barrier for adoption in undergraduate and postgraduate teaching.

Architecturally, the solver maps cleanly to discrete-time state machines, suggesting natural translatability into FPGA/ASIC implementations. We propose BioSynapStudio as both a practical environment for validating and teaching SNUFA today, and as a potential blueprint for neuromorphic substrates grounded in biological realism in the future.