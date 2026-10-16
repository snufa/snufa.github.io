# Audio Event Classification with Spiking Neural Networks and e-prop

**Authors:** Lucía Torrescusa-Rubio, Xavier Otazu
                           
**Presenting author:** Lucía Torrescusa-Rubio (Xavier Otazu if Lucía is unable to attend).

**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

Eligibility propagation, or e-prop (Bellec et al., 2020), offers an online alternative for training recurrent Spiking Neural Networks (SNNs) by combining local eligibility traces with neuron-specific learning signals, approximating gradient-based learning without backpropagation through time. In this work, we evaluate a recurrent SNN using the e-prop learning principle and compare it to a Convolutional Neural Network (CNN) trained by backpropagation to solve a particular Machine Learning problem: multilabel drum onset detection from audio.

We implement a recurrent SNN with both leaky and adaptive leaky integrate-and-fire neurons, and train it using e-prop to classify drum events from time-frequency audio representations. The same task is also addressed with a CNN trained with backpropagation, providing a conventional baseline. The models are evaluated using micro- and macro-F1 scores, with particular attention to class imbalance and low-data training regimes.

Results suggest that SNNs trained with e-prop can approximate the overall performance of CNNs trained with backpropagation, remaining approximately 10 percentage points below the CNN in F1 score for the three drum instruments with the most representative sounds when using the full training set. In low-data experiments, including one-shot (one training sample), five-shot and ten-shot settings, the e-prop model outperforms the CNN by approximately 10 percentage points in micro-F1. These findings support the potential of eligibility-based learning as a biologically plausible and data-efficient alternative for machine learning tasks (e.g., temporal audio classification) and motivate further work on online learning.