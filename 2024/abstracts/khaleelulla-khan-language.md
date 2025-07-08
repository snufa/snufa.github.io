# Language Modeling on a SpiNNaker2 Neuromorphic Chip 

**Authors:** Khaleelulla Khan Nazeer, Mark Schoene, Rishav Mukherji, Bernhard Vogginger, Christian Mayr, David Kappel, Anand Subramoney
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

As large language models continue to scale rapidly in size, the computational power required to run them increases significantly, raising concerns about energy efficiency. Event-based networks running on neuromorphic devices offer a promising solution to reduce the energy demands of inference. However, most event-based networks designed for neuromorphic hardware, including spiking neural networks (SNNs), have struggled to match the performance of traditional architectures like LSTMs in language modeling.

In this work, we address this by demonstrating the first successful implementation of a language model on SpiNNaker2 neuromorphic hardware, utilizing the recently introduced event-based architecture known the EGRU. SpiNNaker2, a many-core neuromorphic chip optimized for large-scale asynchronous processing, is specifically designed to handle dynamic sparsity or events efficiently and the EGRU architecture leverages these hardware features to achieve task performance comparable to LSTMs, while also significantly reducing energy consumption. We show a 5-18x reduction in energy consumption for single-batch inference compared to a GPU in language modelling as well as DVS gesture recognition while retaining competitive performance.