# Accurate detection of precise spiking motifs in neurobiological data

**Authors:** Laurent Perrinet

**Presentation type:** Short talk

## Abstract

Recently, there has been growing interest in exploring the hypothesis that neural activity conveys information through precise spiking motifs. To investigate this hypothesis, various algorithms have been proposed to detect such motifs in spiking activity recorded from populations of neurons. In this study, we present a detection model that takes the form of logistic regression combined with temporal convolution. A key advantage of this model is its differentiability, which allows us to formulate a gradient descent on any appropriate loss. We prove its efficiency on synthetic data for which the ground truth is available to use supervised learning. However, this ground truth information is not available for neurobiological data, where a self-learning procedure is required. We show that a contrastive learning method can recover the synthetically generated spiking motifs without knowing the ground truth. In the future, we aim to extend this method to real neurobiological data to explore and detect spiking motifs in a more natural and biologically relevant context.