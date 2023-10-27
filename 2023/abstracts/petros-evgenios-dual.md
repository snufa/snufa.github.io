# The dual nature of synaptic homeostasis: Interaction between fast and slow processes

**Authors:** Petros Evgenios Vlachos

**Presentation type:** Poster

## Abstract

Hebbian plasticity mechanisms tend to be unstable and need to be reined in by compensatory mechanisms to prevent pathological network activity. Homeostatic synaptic scaling has been shown to up- or down-regulate synaptic efficacies to maintain neural activity levels at a specific set point. However, typical timescales of homeostatic synaptic scaling are too slow to compensate for the runaway growth of synapses due to Hebbian mechanisms. In contrast, heterosynaptic plasticity has been shown to act more quickly, but it is unclear if and how it could regulate activity levels in a homeostatic fashion.

Here we propose an integrated model of heterosynaptic plasticity and homeostatic synaptic scaling based on the availability and redistribution of synaptic building blocks such as neurotransmitter receptors or synaptic scaffolding molecules. In the model, synapses compete for a finite amount of building blocks, whereas the total amount of available building blocks is homeostatically regulated. Our model avoids the assumption of existing synaptic scaling models that individual synapses have access to non-local information such as the firing rate of the neuron.

Concretely, we simulate a leaky integrate-and-fire neuron with excitatory (NE = 100) and inhibitory (NI = 25) conductance-based input synapses. Incoming spike trains are generated from independent Poisson processes. A classic spike-timing-dependent plasticity rule adapts excitatory synaptic weights. A heterosynaptic plasticity mechanism ensures that synapses grow at the expense of other synapses. This is realized through a multiplicative normalization scheme. The total amount of available synaptic building blocks is regulated with a simple homeostatic control law to achieve a predefined target activity level. Parameter values are set to replicate experimental results.

We demonstrate that the model prevents runaway growth of synapses at rapid timescales while it homeostatically regulates neuronal activity at much slower timescales. Overall, our results highlight the importance of multiple timescales of synaptic regulation.
