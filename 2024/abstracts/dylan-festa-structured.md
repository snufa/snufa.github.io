# Structured stabilization in recurrent neural circuits through inhibitory synaptic plasticity

**Authors:** Dylan Festa, Claudia Cusseddu, Julijana Gjorgjieva
                           
**Presenting author:** Dylan Festa

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Inhibitory neurons (I), like their excitatory (E) counterparts, adjust synaptic efficacies in response to neural activity. Contrary to the traditional view of inhibition as a purely global activity regulator, recent studies highlighted how structured E/I connectivity motifs can further refine neural computations. These motifs take essential roles in tuning of receptive fields, learning of representations, predictive coding, and in the regulation of the network dynamics.

Despite numerous characterizations of inhibitory plasticity rules, integrating them into a cohesive understanding of inhibition’s various aspects — circuit stabilization, motif formation, and specific motif selection — remains challenging. Here we introduce a generalized inhibitory spike-timing dependent plasticity (iSTDP) framework, and distinguish its effects into two components: one dependent on firing rates, which tunes inhibitory synapses broadly and hinders motif formation, and another exclusively regulated by higher order statistics, which instead fosters sparser, more structured connectivity. 

We demonstrate both analytically in E/I circuit motifs and numerically in large spiking recurrent neural networks (RNNs), that iSTDP rules can selectively reinforce either mutually connected E/I pairs or lateral inhibition, where an inhibitory neuron connects to an excitatory neuron that does not directly connect back to it. In a one-dimensional ring network with two inhibitory populations, each following a distinct iSTDP rule, the excitatory population self-organizes into a Mexican-hat-like effective connectivity. This leads to emergent dynamical properties such as surround suppression and modular spontaneous activity. 

Our theoretical framework highlights the interplay between iSTDP rules, circuit structure, and neuronal dynamics. By promoting structured, self-organized stabilization, these rules offer a mechanism for understanding how inhibitory plasticity shapes network function, going beyond the traditional view of inhibition as a global activity modulator.