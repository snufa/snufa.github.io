# Integrating biological activation functions into artificial neural networks

**Authors:** Katarina Vulić, Joël Küchler, Jona Schulz, Haotian Yao, Sean Weaver, Stephan Ihle, Jens Duru, János Vörös
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Despite being inspired by biological neuronal networks (BNNs), artificial neural networks (ANNs) have fundamental differences from their biological counterparts. While ANNs excel at solving complex problems across various domains, BNNs outperform them in terms of energy efficiency and processing highly complex parallel inputs. However, the mechanisms behind these advantages remain unclear, making it challenging to integrate them into artificial computation.

It has been shown that biological neurons exhibit a characteristic sigmoid-like firing rate response (i.e. activation function), termed bio-sigmoid, as a function of external input (e.g., stimulation voltage). By culturing neurons within polydimethylsiloxane (PDMS) microstructures on microelectrode arrays (MEAs), we can generate biological networks with defined input/output relations and produce the bio-sigmoid function through voltage stimulation. This bio-sigmoid function can then be used as an activation function in an ANN, which has demonstrated good performance on XOR classification.

To achieve this, we developed an online stimulation and recording interface for the MEA system to perform inference on ANN models. We trained the ANN using a simulated noisy sigmoid activation function to develop robust weights suitable for testing with the inherently noisy biological neurons. Our results highlight the benefits of injecting noise during ANN training, showing high classification accuracies on XOR when using the biological neural network response as the activation function. These findings suggest promising potential for creating biohybrid neural interfaces for computation and bridging the artificial and biological information processing.