# Time-reversed event-based simulations enable memory-efficient exact gradient descent in spiking neural networks

**Authors:** Christian Klos
                           


**Presentation type:** Talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

The ability to train spiking neural networks with gradient descent is essential for neuromorphic computing and provides an important tool for building models of biological neural networks. The most common approach relies on timestep-based simulations and surrogate gradient descent. Recently, an alternative based on event-based simulations, which iterate over spikes rather than timesteps, has gained traction. This approach is numerically precise and enables the computation of exact, spike time-based gradients using automatic differentiation. However, a major obstacle to its practical use is that backpropagation requires storing state variables at every spike, leading to prohibitive memory scaling.

Here, we show that time-reversed simulations are particularly well suited to addressing this memory-efficiency problem. They can be used to recompute state variables in parallel with error backpropagation, thereby avoiding the need to store them. A practical challenge is that time-reversed simulations tend to deviate from the forward pass because of numerical discretization or floating-point errors, leading to inaccurate gradients. In event-based simulations, these problems are absent or can be readily minimized. Specifically, numerical discretization errors do not arise due to the use of neuron models with closed-form solutions between spikes. To mitigate remaining floating-point errors while keeping memory use low, we store only the spike times and the identities of the spike-generating neurons and use this information to guide the time-reversed simulations. This also eliminates single neuron model-dependent ambiguities in identifying the previously spiking neuron in a time-reversed simulation step. Such ambiguities arise when reaching the reset potential does not necessarily imply a previous spike and voltage reset, as typically in leaky integrate-and-fire neurons.

Leveraging automatic differentiation frameworks, we implement our approach in a model-agnostic way and evaluate it using standard setups from theoretical neuroscience and neuromorphic computing.