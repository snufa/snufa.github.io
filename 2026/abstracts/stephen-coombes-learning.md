# Learning with delays: white-matter plasticity and timing in spiking networks

**Authors:** Stephen Coombes, Rüdiger Thul
                           


**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Signal transmission delays are ubiquitous in the brain, yet they are often treated as fixed constraints rather than adaptable components of neural computation. In particular, activity-dependent changes in axonal conduction speed provide a potential mechanism for white-matter plasticity, allowing networks to regulate the relative timing of signals arriving from spatially distributed neuronal populations.

We study this idea in networks of spiking neurons with explicit conduction delays. Using an event-based dynamical description, we develop a framework for understanding how delay plasticity reshapes collective spike timing and phase locking. This provides a natural setting in which to explore communication through coherence: rather than modifying synaptic strength alone, plastic changes in conduction delays can tune the arrival times of spikes and thereby promote or suppress coherent interactions between neuronal populations.

We show how biologically motivated activity-dependent rules for conduction delays can reorganise the timing structure of a network, and how the resulting dynamics can be understood using mathematical reductions that retain the discrete nature of neuronal spiking. This suggests that white-matter plasticity may be viewed as a form of temporal learning, in which computation is performed not only through which neurons interact and with what strength, but through when their signals arrive.

Time permitting, we will also discuss more recent work on gradient-based learning of transmission delays in spiking networks. Motivated by recent extensions of EventProp to delay learning, we develop a more general formulation based on saltation operators for propagating sensitivities through spike and transmission events.