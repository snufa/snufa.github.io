# On the geometry of recurrent spiking networks

**Authors:** Josue Casco-Rodriguez
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Biological neural networks are recurrent and transmit information via discrete spikes. However, neural network theories largely focus on deep feedforward architectures with continuous activations, and it is not clear to what extent these theories are relevant to the analysis and optimization of recurrent spiking neural networks (SNNs). We propose to study the geometry of SNNs as piecewise-constant functions, which we visualize with our new algorithm, SplineCam-SNN. We first study how the parameters of deep SNNs affect their input-output geometry. In contrast to deep networks with continuous activations, recurrent (synaptic) weights appear to have a more limited influence on the geometry than skip connections, leakages, and delays. With these insights, we examine plasticity: training all parameters via gradient descent aligns input-output geometry around data, while limiting optimization to synaptic weights (like in STDP) limits this alignment. Our findings emphasize the importance of skip connections, leakages, and delays for training SNNs, and suggest that these parameters may be promising targets for future plasticity algorithms.