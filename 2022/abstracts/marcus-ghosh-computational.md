
# On the computational role of multimodal units 

**Authors:** Marcus Ghosh, Gabriel Béna, Nicolas Perez-Nieves, Volker Bormuth, Dan F. M. Goodman  

**Presentation type:** Poster

## Abstract

We continuously detect sensory data, like sights and sounds, and use this information to guide our behaviour. Though, rather than relying on single sensory channels, which are inherently noisy, we merge information across our senses and leverage this combined signal. Across species, this process (multimodal integration) has been shown to reduce noise and enable faster and more accurate decision making. However, how biological neurons implement multimodal computations remains an open question.  

Prior work suggests that multimodal neurons perform linear computations, I.e., weight and sum evidence across channels. However, we demonstrate that this strategy is only optimal when the rate of evidence is constant over time, and that when the amount of evidence varies realistically, a nonlinear strategy becomes optimal.  

Using surrogate gradient descent, we demonstrate that spiking neural networks can be trained to solve multimodal tasks of this form (where the rate of evidence varies over time) and we develop a set of minimal network models which allow us to succinctly describe the underlying computations in our networks. Using these models, we demonstrate that while many distinct solutions exist for different forms of our tasks, only a subset of solutions generalise across variations.  

Ultimately, our work emphasises the role of nonlinear computations in multimodal integration, and provides novel tasks and models for exploring this in biological systems.  