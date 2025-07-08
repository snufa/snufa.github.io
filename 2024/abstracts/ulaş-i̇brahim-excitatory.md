# Excitatory and inhibitory neurons exhibit distinct roles for task learning, temporal scaling, and working memory in recurrent spiking neural network models of neocortex

**Authors:** Ulaş İbrahim Ayyılmaz, Antara Garani Krishnan, Yuqing Zhu
                           
**Presenting author:** Ulaş İbrahim Ayyılmaz

**Presentation type:** Talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

The brain encodes information through the spiking dynamics of recurrent excitatory (E) and inhibitory (I) neurons. Recurrent Spiking Neural Networks (RSNNs) have the potential to shed light on neurobiological computation. While inhibition and excitation are fundamental to cortical dynamics, the specific roles of individual E and I neurons, as well as distinct I neuron subclasses, remain unclear. To explore these roles, we constructed biologically plausible RSNNs using leaky integrate-and-fire neurons and trained them on variations of a temporal task. We find that distinct interneuron subclasses create varied timescales of behavior, resulting in improved temporal task performance.
For biological realism, we included a refractory period, sparse connectivity, and a 4:1 E:I neuron ratio. We developed two models: one with a single I neuron class and another with three distinct I neuron subclasses (PValb, SST, 5Htr3a). Both models were trained on temporal tasks. The three-I-class model demonstrated better excitation regulation, smoother phase transitions, and improved task performance, suggesting that diverse inhibition enhances computation.
To investigate further, we trained both models on a sine wave generation task using inputs of amplitude, period, and a clock-like signal. Specific E and I neurons tuned to different phases drove positive or negative sine wave production. The three-I-class model exhibited more pronounced temporal scaling in response to period variation, reinforcing the role of diverse inhibition.
We also explored tasks with varying amplitude and period. Higher inhibitory activity in the varying amplitude task indicated that I neurons play a key role in regulating excitation for amplitude control. In a short-term memory task, where inputs were limited, excitatory activity increased in importance to support self-sustained network dynamics.
Our findings highlight how diverse inhibitory neurons, alongside individual E and I neurons, contribute to temporal computation in the neocortex.