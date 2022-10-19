
# Temporally shifted STDP rule reveals synapses crucial for learning

**Authors:** Maayan Levy, Tim P. Vogels

**Presentation type:** Poster

## Abstract

In order to understand how organisms learn, one needs to specify which subset of synapses should be modified and in what way. Identifying this subset of synapses has proven difficult; in the majority of networks all synapses are trained, often using an error or a global learning rule which might not be biologically plausible. Here, we search for a subset of synapses required to learn MNIST while considering three realistic constraints on learning: first, learning is often unsupervised. Second, the substrate of learning is local. And finally, the distribution of synaptic efficacies (weights) measured in the brain is heavy-tailed.
We train a recurrent, conductance-based spiking neural network (rSNN) of leaky-integrate-and-fire neurons to classify MNIST digits with only a Hebbian learning rule, namely, spike-timing dependent plasticity (STDP). Initial weights are sampled from a lognormal distribution. The rSNN receives poisson inputs from an input layer with receptive fields tiling the MNIST image, and rates reflecting the luminance values of the pixels. Input layer projections to rSNN are random with 8% probability, and are held constant. To train the network, we employ a 2 ms temporally shifted STDP rule on recurrent excitatory to excitatory synapses. Under this rule, synchronous spiking causes depression rather than facilitation, hence preventing inflation of synaptic weights and the resulting firing rates. In other words, no homeostatic mechanism is used.
We find that this learning rule is self-stabilizing, preserving the distribution of synaptic efficacies and low firing rates. Training sparsifies the number of active neurons for each stimulus class, forming ensembles with very little overlap, beneficial for accurate classification. We show that with random network architecture and under the biological constraints in our model, learning depends on retention, rather than modification, of synapses with (near) synchronous pre- and post- synaptic spiking.