# Hardware multichannel time encoding with leaky integrate-and-fire neurons

**Authors:** Alessandro Macuglia, Giacomo Indiveri
                           
**Presenting author:** Alessandro Macuglia

**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

It is well known that single neurons can faithfully encode time-varying signals using pulse-frequency modulation if the signal bandwidth is low enough.
Recent theoretical work has demonstrated, using time-encoding techniques, that populations of leaky integrate-and-fire neurons can collectively encode and reconstruct bandlimited signals, even if their frequencies exceed the intrinsic firing rates of individual neurons.
However, this relied on precise and identical neuron models, with specific temporal shifts in their firing rates.
In this work, we demonstrate the feasibility of implementing multi-channel time encoding using populations of neurons with intrinsic variability and validate this with a mixed-signal neuromorphic device that integrates analog silicon neurons subject to device mismatch.
We converted high-frequency sinusoidal inputs, ranging from 1 to 70 Hz, into spike trains and delivered them to multiple silicon neurons in parallel with a maximum firing rate of 40 Hz.
We combined the population output and reconstructed the original signal using two kernels: an exponential kernel to preserve biological plausibility and a theoretically optimal sinc kernel to enhance precision.
We assessed reconstruction accuracy by calculating the root mean square error (RMSE) between original and reconstructed signals.
Experimental results confirm that reconstruction precision increases with population size: larger ensembles yield lower RMSE, consistent with theory.
At higher input frequencies, however, performance saturates, highlighting limitations from kernel choice and hardware variability.
Importantly, the intrinsic mismatch between neurons, typically considered a limitation, effectively provides the temporal shifts required by the theoretical model.
These findings constitute an experimental validation of multichannel time-encoding principles in spiking neurons.
They demonstrate that hardware imperfections can be leveraged as functional features, enabling efficient population-based encoding of high-frequency signals.
This work bridges theoretical models with practical neuromorphic implementations, with implications for brain-inspired computation and energy-efficient sensory processing.