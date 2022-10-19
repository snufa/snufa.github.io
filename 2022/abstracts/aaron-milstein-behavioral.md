
# Behavioral Timescale Synaptic Plasticity (BTSP) for biologically plausible credit assignment across multiple layers via top-down gating of dendritic plasticity

**Authors:** A. Galloni, A. Peddada, A. Milstein

**Presentation type:** Talk

## Abstract

A central problem in biological learning is how information about the outcome of a decision or behavior can be used to reliably guide learning across distributed neural circuits while obeying biological constraints. This “credit assignment” problem is commonly solved in artificial neural networks through supervised gradient descent and the backpropagation algorithm. In contrast, biological learning is typically modelled using unsupervised Hebbian learning rules. While these rules only use local information to update synaptic weights, and are sometimes combined with weight constraints to reflect a diversity of excitatory (only positive weights) and inhibitory (only negative weights) cell types, they do not prescribe a clear mechanism for how to coordinate learning across multiple layers and propagate error information accurately across the network.

In recent years, several groups have drawn inspiration from the known dendritic non-linearities of pyramidal neurons to propose new learning rules and network architectures that enable biologically plausible multi-layer learning by processing error information in segregated dendrites. Meanwhile, recent experimental results from the hippocampus have revealed a new form of plasticity—Behavioral Timescale Synaptic Plasticity (BTSP)—in which large dendritic depolarizations rapidly reshape synaptic weights and stimulus selectivity with as little as a single stimulus presentation (“one-shot learning”).

Here we explore the implications of this new learning rule through a biologically plausible implementation in a rate neuron network. We demonstrate that regulation of dendritic spiking and BTSP by top-down feedback signals can effectively coordinate plasticity across multiple network layers in a simple pattern recognition task. By analyzing hidden feature representations and weight trajectories during learning, we show the differences between networks trained with standard backpropagation, Hebbian learning rules, and BTSP.