# The neural tangent kernel in networks with step-like activation functions

**Authors:** Luke Eilers, Sven Goedeke

**Presentation type:** Poster at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

Although a precise mathematical understanding of artificial neural networks trained with gradient-based methods is still missing, a considerable body of theory has been developed. In contrast, the training of networks with discontinuous activation functions in the context of gradient-based methods and backpropagation poses a major challenge, in particular with piecewise constant activation functions, which do not propagate gradients. This concerns areas such as neuromorphic computing and the training of spiking neural networks in theoretical neuroscience. To overcome this challenge, the method of surrogate gradient learning, also known as straight-through estimation, has been proposed. As this method works well in practice, the derivation of a theoretical basis is desirable.

Here, we explore the gradient-based learning of networks with step-like activation functions in the infinite width limit using the neural tangent kernel (NTK). As a first step, we use existing results on the NTK to analyze gradient-descent training for infinite width networks with sign activation function. The ill-posedness of this approach in the regression case is demonstrated and a connection to Nadaraya-Watson estimators in the classification case is established. Second, we generalize the existing key theorems on the NTK to the surrogate gradient setting by considering an asymmetric kernel. This allows us to analyze the surrogate gradient learning of infinite width networks with sign activation function, and leads to predictions useful for large width networks, which we test using numerical simulations. In particular, significant progress is made toward a theoretical foundation of surrogate gradient learning in large width networks. Finally, we derive formulas characterizing the influence of different surrogate derivatives and identify their regularizing effect in a special case. We expect our work to also provide a starting point for analyzing surrogate gradient learning of spiking neural networks in the infinite width limit.