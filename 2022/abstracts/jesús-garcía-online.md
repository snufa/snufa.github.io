
# Online Learning via Constrained Parameter Inference (COPI)

**Authors:** Jesús García Fernández

**Presentation type:** Poster

## Abstract

How learning is accomplished in the brain remains an unsolved problem. While backpropagation has been successful in training artificial neural networks, and approximations can be used for training spiking variants, its biological implausibility makes it an unlikely candidate for explaining learning in the brain. Biologically plausible learning mechanisms, an important research topic in computational neuroscience, can potentially uncover how the brain learns from experience. There is also an increasing interest in this topic in the ML community as the locality of these mechanisms might be suitable for neuromorphic hardware. The downside is that existing bio-plausible models are still far from reaching backpropagation's performance in practical tasks. 
Recently, we have developed a new learning mechanism which formulates learning as a process of constrained parameter inference (COPI). COPI aims to integrate the main desired features for bio-plausible learning, such as the sole use of local information for parameters, enabled by decorrelating their activity, and top-down perturbation of neural states, which assigns credit to neuron activities instead of parameters. It also differs from other approaches by only needing a single state measurement to infer the updates (bio-plausible methods usually rely on activity contrasts at different moments in time — see the NGRAD hypothesis). Furthermore, it can operate in discrete as well as continuous-time networks. 
Here, we explore the application of this learning principle to multi-layer spiking neural networks (SNNs) and demonstrate its performance in both single- and multi-layer networks. We also compare different assignment credit methods, such as Back Propagation (BP), Target Propagation (TP) and Feedback Alignment (FA). Results show similar performance on spiking and non-spiking networks at an image recognition task, and competitive performance with respect to rate-based feedforward neural networks trained with backpropagation. 