# Distributing task-related neural activity across a cortical network through task-independent connections

**Authors:** Christopher Kim

**Presentation type:** Short talk

## Abstract

A network of excitatory and inhibitory (EI) spiking neurons, operating in a regime where strong excitation and inhibition are dynamically balanced, has been a seminal model for explaining asynchronous and correlated spiking activities of cortical neurons. However, due to its strong EI synaptic interactions, training large-scale balanced spiking networks to perform tasks has posed significant challenges in developing training algorithm and trainable network architecture.

In this work, we demonstrate that, using a widely used recursive least squares algorithm, neurons in the balanced network can learn to generate arbitrary firing rate patterns. We show that modifying plastic synapses much sparser than the initial EI connections is sufficient to produce target activity patterns fluctuating around the spike threshold. 

We apply this training scheme to train a subset of excitatory neurons in the balanced network to reproduce the spiking rate patterns of Pyramidal neurons recorded from motor cortex involved in memory-guided decision-making task. We find that inhibitory neurons in the balanced network, which are not trained, also generate firing rate patterns similar to the trained excitatory neurons, demonstrating that the activity learned in a subset of neurons can spread to the entire network. Moreover, the firing rate patterns of the untrained inhibitory neurons closely match the rate patterns of fast-spiking neurons in the motor cortex, held out from training dataset. This suggests that the strong EI connections, creating the balanced state and independent of the task, could be involved in spreading task-related activities across the cortical network. Analysis of optogenetic perturbation responses suggests that cortical network could operate in the balanced regime.

In sum, our work suggests that task-related activity observed in cortical regions during behavior can emerge from a subset of neurons with sparse synaptic reorganization and propagate to the rest of the network through the strong, task-independent synapses. 