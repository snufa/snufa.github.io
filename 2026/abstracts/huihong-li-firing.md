# Firing Rate Homeostasis Improves Learning Through Irregular Spiking

**Authors:** Huihong Li, Daniel Levenstein
                           
**Presenting author:** Huihong Li

**Presentation type:** Talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Neuronal activity in the mammalian forebrain is characterized by irregular spiking at low rates, which are maintained by plastic synapses and excitability. This “homeostatic” plasticity is similar to regularization in machine learning, where auxiliary losses that minimize the activity of neural networks shape the representations they learn, improving performance and generalization. Whether homeostatic plasticity serves a similar function in the brain, where neurons communicate with spikes rather than scalar rates, or if it simply minimizes energy expenditure, remains unknown.

To investigate the interplay between homeostatic plasticity, spiking properties, and computation, we trained recurrent spiking neural networks with eligibility propagation on reinforcement learning tasks, including standard benchmarks and naturalistic foraging tasks. We found that homeostatic firing rate regularization improves learning and task performance, producing networks with brain-like spiking. Unlike rate-based networks, spiking networks were most effective with “loose” target firing rate homeostasis, where a homeostatic loss of intermediate strength brought neurons toward a specified firing rate. As a result, firing rates were broadly distributed around the target, with fewer silent or high firing rate neurons than their activity-minimizing or unregularized counterparts.

In this homeostatic regime, networks developed super-Poisson irregular spiking, mixed selectivity for environmental variables, and fluctuating population activity with intermediate dimensionality. Network performance was directly correlated with these brain-like spiking properties, while a loss that penalized super-Poisson spiking impaired performance. Interestingly, we found that homeostasis predominantly stabilized learning, as network performance persisted without continued homeostasis despite drifting away from the irregular spiking regime, which reduced their ability to learn new tasks.

Finally, we found that inhibitory plasticity was sufficient to match gradient-based regularization performance in networks constrained by Dale’s law. These results suggest a close relationship between firing rate homeostasis, irregular spiking, and computation, in which loose target-rate homeostasis maintains an optimal regime for learning characterized by irregular spiking.
