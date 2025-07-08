# Evolving spiking neural networks for predator avoidance

**Authors:** Mason McGill, Pietro Perona
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Animals can learn many things from their environment, but an individual animal can't learn from being eaten. Predator-avoidance strategies belong to a broad class of behaviors that develop—at least partially—at the population level, through natural selection. What does this evolution process look like as it's taking place? And what factors influence how quickly it converges? 

To start to answer these questions, we constructed simulation environments inspired by the ecological niche occupied by the fruit fly—an animal whose predator-avoidance strategy has been studied quantitatively. In these environments, virtual foragers must make stay-or-flee decisions by integrating information from ambiguous sensory cues over time, using a genetically encoded spiking neural network. And the foragers who best balance caution (fleeing when a predator is nearby) with metabolic efficiency (ignoring potentially frightening stimuli when they are safe) will on average outbreed their competitors.

We developed specialized GPU kernels to enable simulating millions of forager lifetimes per second, and analyzed how populations evolved over tens of thousands of generations, across a variety of conditions. We found that the evolved foragers exhibited properties observed in real fruit flies, and could attain over 99% of the fitness of a stay-or-flee controller generated using a reinforcement learning algorithm with direct access to the environment’s dynamics.

Additionally, we found that high-fitness networks are discovered more quickly in environments where subpopulations move around slowly and can remain isolated from each other for many generations. In these environments, subpopulations with incompatible genotypes compete for territory, with bands of low-fitness hybrids forming at territorial boundaries. We also found that populations evolving in highly dynamic environments adapt to change faster than populations evolving in static or infrequently changing environments. These convergence rate observations may be particularly relevant for future efforts to evolve spiking neural networks, for applications in both engineering and computational biology.