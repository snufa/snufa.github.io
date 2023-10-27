# Enhancing the Cleo experiment simulation testbed to support all-optical control, multi-channel optogenetics, and easier integration into data analysis pipelines

**Authors:** Kyle A. Johnsen, Nathanael A. Cruzado, Adam S. Charles, Christopher J. Rozell

**Presentation type:** Poster at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

Recent advances in systems neuroscience methods enable exciting new kinds of experiments. One of these is closed-loop optogenetic control, which combines simultaneous photostimulation and recording to precisely control mesoscale neural activity on the order of milliseconds. However, the difficulty of implementing such experiments can slow development and impede adoption. To address this challenge, we have developed the Cleo (Closed Loop, Electrophysiology, and Optophysiology) experiment simulation testbed, which allows researchers to prototype complex experiments in silico. It does this by wrapping a Brian spiking neural network model, enabling closed-loop control as well as the injection of recording and stimulation devices. 

While we have previously demonstrated Cleo’s capabilities to simulate electrode recording and optogenetic stimulation, we now present a number of improvements to enhance Cleo’s utility and usability in modern experimental paradigms. The first is support for two-photon imaging with flexible specification of genetically encoded calcium indicator models. Second is holographic photostimulation, which, combined with the first, allows for the simulation of all-optical control. Third, we have greatly facilitated the simultaneous use of multiple light sources and opsins, allowing for advanced paradigms such as bidirectional or multi-channel stimulation. Finally, Cleo can now export recording and stimulation data via Neo, which can in turn convert to a number of proprietary formats and thus be easily incorporated into pre-existing data analysis pipelines. 

As before, the package is accompanied by detailed online documentation including user-friendly tutorials. This documentation, as well as open-source code, can be found at the links below:

Documentation: https://cleosim.readthedocs.io
Code repository: https://github.com/siplab-gt/cleo