# SNN Model Training Evaluated Through Loss Landscapes

**Authors:** Thomas Summe, Siddarth Joshi

**Presentation type:** Poster at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

Training SNNs is a key step in developing event-based models that can adapt to changing environments and learn from continuous data streams in real-time. While BPTT with surrogate gradients is currently the defacto method of training state-of-the-art SNNs, many alternative training algorithms have recently emerged. We demonstrate how, despite sometimes delivering similar accuracy, these algorithms can result in models with dramatically different parameters. We modify Randman to create a rate- and a time-encoded dataset. We evaluate these models via their training trajectories and gradient direction to better understand their performance on these datasets.