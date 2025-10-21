# Anticipation in Multi-Agent Systems: A Dynamical Systems Approach to Self-Coordination

**Authors:** Ali Baokbah, Iran Roman, Ji Chul Kim, Edward Large
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

In this work, we propose an alternative approach to self-coordination in multi-agent systems. Dynamical systems possess unique properties, which enable them to exhibit strong anticipation, as hypothesized previously. We examined four dynamical systems: Hopf oscillators, the Wilson-Cowan model, the FitzHugh-Nagumo model, and the Rössler system and their ability to exhibit anticipating synchronization when coupled via delayed feedback. We observed anticipatory behavior in the systems when arranged in a “leader-follower” configuration. The anticipation persisted across a range of coupling strength and time delay values. We then trained recurrent neural networks (RNNs) to learn the dynamics and trajectories of Wilson Cowan and Hopf oscillators. The trained models successfully reproduced the trajectories of the original Hopf and Wilson-Cowan systems without additional training or external input, indicating that the networks internalized the dynamics of the systems. Furthermore, RNN based agents exhibited spontaneous oscillatory activity and consistent negative phase shifts when connected as a “leader-follower” pair via their hidden states. These observations were in line with strong anticipation that was observed in the original systems. Our findings suggest that anticipatory behavior is not strictly learned, but an emergent property of delay-coupled systems. This shows that physics based models can achieve zero-shot learning of anticipating synchronization, which offers a promising space for resource efficient multi-agent coordination.