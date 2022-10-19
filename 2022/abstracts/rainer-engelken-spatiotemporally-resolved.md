
# A spatiotemporally-resolved view of cellular contributions to chaos and information flow in spiking neural networks

**Authors:** Rainer Engelken, Fred Wolf

**Presentation type:** Poster

## Abstract

Information in the cortex is processed by a deeply layered system of neural circuits. How well streams of spikes from one circuit can control spiking dynamics in subsequent cortical processing stages is essential for information processing. In particular noise entropy arising from the sensitivity to initial conditions of recurrent cortical circuits can limit the information conveyed about the sensory input. Directly measuring entropy in a high-dimensional system, however, is computationally intractable even in models. Ergodic theory has been proposed as a tractable approach to measure dynamical entropy production of large recurrent spiking networks [Monteforte 2010, Lajoie 2013, 2014, 2016]. Earlier studies used constant external input. However, how the statistics of input spike trains controls the recurrent dynamics has not yet been analyzed.
To address this challenge, we developed an approach for balanced networks driven by external streams of spike trains and calculate their full Lyapunov spectra, yielding the dynamical entropy production and attractor dimensionality in efficient, numerically exact event-based calculations.
We found that increasing the input rate or coupling strength aids in controlling the driven target circuit, reflected both in reduced trial-to-trial variability and in a decreasing dynamic entropy production. For sufficiently strong input, we observed a transition to complete network state control. Surprisingly, this transition generally does not coincide with the transition from chaos to stability but occurs at larger values of external input strength. Intriguingly, controllability of spiking activity is facilitated when neurons in the target circuit have a rapid AP initiation. 
Our study predicts that rapid AP initiation of target neurons decreases trial-to-trial variability and augments information flow. These results can also be used to design control strategies for emerging optogenetic approaches to the causal interrogation of circuit function and dynamics. 
