
# A biologically plausible inhibitory plasticity rule for world-model learning in SNNs

**Authors:** Zhenrui Liao*, Darian Hadjiabadi*, Satoshi Terada, Ivan Soltesz, Attila Losonczy

**Presentation type:** Talk

## Abstract

Memory consolidation is the process by which recent experiences are assimilated into long-term memory. In animals, this process requires the offline replay of sequences observed during online exploration in the hippocampus. Recent experimental work has found that salient but task-irrelevant stimuli are systematically excluded from these replay epochs, suggesting that replay samples from an abstracted model of the world, rather than verbatim previous experiences. We find that this phenomenon can be explained parsimoniously and biologically plausibly by a Hebbian spike time-dependent plasticity rule at inhibitory synapses. Using spiking networks at three levels of abstraction--leaky integrate-and-fire, biophysically detailed, and abstract binary--we show that this rule enables efficient inference of a model of the structure of the world. While plasticity has previously mainly been studied at excitatory synapses, we find that plasticity at excitatory synapses alone is insufficient to accomplish this type of structural learning. We present theoretical results in a simplified model showing that in the presence of Hebbian excitatory and inhibitory plasticity, the replayed sequences form a statistical estimator of a latent sequence, which converges asymptotically to the ground truth. Our work outlines a direct link between the synaptic and cognitive levels of memory consolidation, and highlights a potential conceptually distinct role for inhibition in computing with SNNs.