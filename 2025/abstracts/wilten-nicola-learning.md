# Learning in Spiking Neural Networks: A Backpropagation-Compatible Architecture Using Conductance Neurons

**Authors:** Navid Akbari, Kai Mason, Aaron Gruber, Wilten Nicola
                           
**Presenting author:** Navid Akbari

**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Spiking Neural Networks (SNNs) strive to replicate the brain's computational efficacy and temporal processing. Training SNNs that are constructed with biologically detailed neuron models that accurately reflect neurobiology presents an important obstacle. This study introduces an SNN architecture that is centered on the Morris-Lecar (ML) neuron, a conductance-based model that is recognized for its ability to reproduce a variety of neuronal dynamics, including Type I/II excitability. The ML model's inherent smoothness and differentiability enable direct end-to-end training through Backpropagation Through Time (BPTT). Our architecture further incorporates neurobiological realism by incorporating separate, recurrently connected excitatory and inhibitory ML neuron populations that interact via conductance-based synapses. We demonstrate the efficacy of this approach by achieving high performance in image classification (97.78\% MNIST, 86.98\% Fashion-MNIST) and also by autonomously generating complex nonlinear dynamics, such as the chaotic attractor of the Lorenz system and the limit cycle of the Van der Pol oscillator. To the best of our knowledge, this work is the first direct BPTT training of an ML-based SNN that incorporates these structural and functional biological aspects for both pattern recognition and complex temporal generation. These results demonstrate the feasibility of employing biophysically detailed, differentiable neuron and synapse models to create SNNs that function as more realistic paradigms of neural computation.