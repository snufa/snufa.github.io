# Evolving reward-driven synaptic learning rules in Spiking Neural Networks for simple RL tasks

**Authors:** Napat Sahapat, Yeshwanth Bethi, Sergio Chevtchenko, Saeed Afshar
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

Over the years, there had been many proposed synaptic plasticity rules for SNNs, from Hebbian to STDP to Anti-Hebbian, and everything in between. While these rules have been grounded in neuroscience and able to perform well in many unsupervised and supervised tasks, we are not restricted to brain-inspired rules; in fact, given how most SNNs are simplified abstractions of neural systems, there may be other rules more suited to these systems. Evolution provides a perfect way of searching for optimal synaptic learning rules; previous studies (Jordan 2021, Confraveux 2025) have looked at evolving learning rules for SNNs, but they were focused on finding realistic and interpretable rules within biologically plausible SNN implementations. In our study, we evolved rules to solve certain RL tasks and within simplified configuration of SNNs. Modelled as a compact MLP / ANN for more expressivity as function approximators, these rules are given access to a few local synaptic variables and global signals and must make use of these inputs to train any new SNN within that family of tasks. Although the discovered rules may not be biologically plausible, this algorithm allows for versatility in situations where previous learning rules such as STDP may not be the best fit. This study is still in its early stage, but already we have found rules that utilised information in unexpected ways: such as depressing weights when encountering positive rewards and vice versa. Through careful experiments with this algorithm, we may even find undiscovered interactions between local synaptic variables or understand why certain rules work within certain constraints.