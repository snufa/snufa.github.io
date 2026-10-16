# Image generation with e-prop: Application to musical symbols.

**Authors:** Gerard Asbert, Alicia Fornés, Xavier Otazu
                           


**Presentation type:** Poster at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Eligibility propagation, or e-prop (Bellec et al., 2020), offers an online alternative for training recurrent Spiking Neural Networks (SNNs) by combining local eligibility traces with neuron-specific learning signals, approximating gradient-based learning without backpropagation through time. In this work, we evaluate a recurrent SNN using e-prop learning principle, and compare it to a Generative Adversarial Network (GAN) trained by backpropagation, to solve a particular Machine Learning problem: image generation.

We implement a recurrent SNN with both leaky and adaptive leaky integrate-and-fire neurons, and train it using e-prop to generate images of handwritten musical symbols. The same task is also addressed with a GAN trained with backpropagation, providing a conventional baseline.

Trained on only 403 historical symbol crops, the model outperforms a symbol-level GAN baseline, lowering the Handwriting Distance from 1.33 to 0.87 with seventy times fewer parameters, and its glyphs, engraved into synthetic scores, pre-train a recogniser to a lower symbol error than either the GAN's glyphs or the real crops engraved in the same way. Beyond reconstruction, the model is controllable: perturbing its spike-train cue yields new instances of a symbol in a given scribal hand, and interpolating the cue moves continuously between copyists. To our knowledge, this is the first spiking generator of offline musical symbol images and the first use of e-prop for image generation of any kind. These results establish spiking networks as a promising foundation for generative modelling in low-resource domains.
