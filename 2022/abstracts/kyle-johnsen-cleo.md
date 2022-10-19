
# Cleo: a simulation testbed for bridging model and experiment in mesoscale neuroscience

**Authors:** Kyle Johnsen, Nathanael Cruzado, Adam Willats, Christopher Rozell

**Presentation type:** Poster

## Abstract

Recent advances in neuroscience technology enable experiments on exciting new spatial and temporal scales, creating opportunities for novel paradigms such as closed-loop optogenetic control of neural activity on the order of milliseconds. At the same time, computational models are becoming ever more powerful for reproducing behavior and neural activity. The complexities of these advances, however, can make it difficult to reap the benefits of bridging model and experiment, such as accelerating experiment development with in-silico prototyping or validating the output of a simulation against experimental data. These aims can be achieved by simulating measurement and manipulation modalities in addition to the underlying neural activity, but a convenient tool does not exist integrating optogenetics, electrode recording, and flexible closed-loop processing with neural population simulations. Thus, we have developed and now present the Closed-Loop, Electrophysiology, and Optogenetics experiment simulation testbed (Cleo): a Python package built on the Brian 2 simulator enabling injection of recording and stimulation devices into a spiking neural network model as well as closed-loop control with realistic latency. We demonstrate its features and usefulness in three virtual experiments and discuss potential extensions and applications for advancing causal neuroscience.