
# Gradient Computation and Analog Neuromorphic Hardware

**Authors:** Luca Blessing

**Presentation type:** Poster

## Abstract

We present our progress implementing the EventProp Algorithm to compute gradients for Analog Neuromorphic Hardware using the example of the BrainScaleS-2 system. While previous gradient-based approaches made use of surrogate gradients and dense sampling of system observables, our approach does only need spike time observations from the system, while being able to incorporate other system observables, such as membrane measurements, in a principled way. This has the potential to enable scalable gradient estimation in large-scale neuromorphic hardware, as continuous measurement of observables would be non-trivial in this case. We will present the theoretical framework for estimating gradients and present results verifying the correctness of the gradient estimation and preliminary experimental results using the BrainScaleS-2 system on toy dataset(s). The algorithms implementation is PyTorch-based and will be publicly available.