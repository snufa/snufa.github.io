# Training SNNs with Local Synaptic Plasticity and Online Error Signal

**Authors:** Mike Stuck and Richard Naud

**Presentation type:** Flash talk

## Abstract

The growing energy demands of large-scale artificial neural networks have led to the need for energy-efficient alternatives. While Spiking Neural Networks (SNNs) offer the promise of low-energy inference when implemented on neuromorphic hardware, existing approaches largely overlook the energy-intensive training phase. Backpropagation is the most effective and widely used training method for neural networks, but it involves calculating the gradient of a loss function with respect to synaptic weights, requiring global access to the state of every neuron over the forward pass. This global memory constraint is incompatible with the structure inherent to neuromorphic hardware and the biological brain, where memory is embedded in synaptic weights.
In this work,we introduce a training algorithm for SNNs that is compatible with neuromorphic hardware. Our method uses a local synaptic plasticity rule and multiplexes feedforward signals with online feedback error signals to steer synaptic updates. The distinction between the feedforward information and feedback error is facilitated by two-compartment neurons consisting of a somatic compartment responsible for integrating feedforward signals and a dendritic compartment for integrating feedback error signals. The algorithm was evaluated on the MNIST digit classification task using rate-encoded inputs. Results show that in shallow networks, our method approaches the performance of state-of-the-art Backpropagation Through Time based training methods, laying the groundwork for energy-efficient training and inference of SNNs directly on neuromorphic hardware.
