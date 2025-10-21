# State-space models can learn in-context by gradient descent

**Authors:** Yudou Tian, Neeraj Mohan Sushma, Nicolo Colombo, David Kappel, Anand Subramoney
                           


**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

The ability of recurrent neural networks to perform in-context learning (ICL) is a hallmark of modern foundation models, with a leading hypothesis being that they implicitly simulate optimization algorithms like gradient descent (GD). However, the precise mechanisms underlying this capability remain elusive. This work provides a direct and explicit construction to demystify this phenomenon in state-space models (SSMs).
We prove that a single-layer SSM, equipped with multiplicative input-output gating, can precisely emulate one step of mini-batch GD on a least-squares objective. This is achieved through a theoretical construction, where the model's architectural priors are matched with a structured input representation that utilizes a sliding window over the context. This construction is not merely an abstraction; we show empirically that randomly initialized models trained on ICL tasks converge to the exact parameters predicted by our theory. Furthermore, this framework naturally extends to multi-step optimization by stacking layers and to non-linear problems by incorporating MLP modules.
Our work reveals a fundamental computational principle: the synergy between a recurrent architecture and a structured data format creates a powerful inductive bias for implementing learning algorithms. This offers a compelling new perspective for understanding biologically plausible learning systems. We hypothesize that similar synergies between specific neural circuit architectures and structured neural representations may underlie learning in the brain. This view expands the notion of the computational power of recurrent networks moving from approximating static functions to approximating the dynamic process of learning itself.