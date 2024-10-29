# Exploring Astrocytic Roles in Context-Driven Synaptic Modulation: A Preliminary Study in Spiking Neural Networks

**Authors:** David Ibáñez
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Sensory signals propagate feedforward through cortical networks, and after processing, new signals propagate back to previously associated features. Evidence shows that within cortical columns, highly territorial astrocytes respond to bottom-up signals with calcium microdomain events, while whole-cell calcium responses are delayed, occurring only after initial processing. Astrocytes respond to synaptic activity and neuromodulators, influencing neuronal activity both synaptically and extrasynaptically by regulating extracellular concentrations, controlling neurotransmitter uptake and spillover, and K⁺ spatial buffering, depending on their calcium activation state.

We propose that context signals are recruited by the apical dendrites of layer 5 pyramidal neurons. Astrocytes respond to this dendritic activity by providing positive feedback to bottom-up pathways when activated and negative feedback when not. In this way, astrocytes modulate pathways to output neurons receiving these context signals, enhancing their activity and leading to long-term potentiation of these synapses, while synapses producing activity under non-activated astrocytes undergo long-term depression.

To test these hypotheses, we used a simple spiking neural network on MNIST. Mimicking a cortical column architecture, 164 neurons and 20 astrocytes were distributed through an input granular layer and ten winner-take-all minicolumns. During training, synaptic activity under astrocytes symbolically activated by context was strengthened, while activity under non-activated astrocytes depressed. The model reached 75% accuracy on the test set. However, when context signals were applied during prediction, accuracy reached 100%. Notably, the model demonstrated robustness to inconsistent contexts, maintaining 50% accuracy with incorrect contextual inputs.

Astrocytic feedback mechanisms have the potential to play a crucial role in context-sensitive learning and perception by modulating neuronal pathways for contextually relevant information. As a behavioral neuroscience student, this basic conceptual model is presented not to provide definitive results, but to open a discussion and encourage the community to consider astrocytes as a valuable addition to spiking neural network architectures and learning algorithms.
