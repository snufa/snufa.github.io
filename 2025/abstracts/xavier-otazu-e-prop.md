# e-prop based SNN for handwritten character generation

**Authors:** Marc Pomar, Aksel Serret, Alicia Fornes, Xavier Otazu
                           
**Presenting author:** Marc Pomar

**Presentation type:** Poster at [SNUFA 2025 online workshop (5-6 Nov 2025)](https://snufa.net/2025)

## Abstract

The e-prop mechanism has been introduced as a biologically plausible learning approach and has demonstrated the capability to address complex machine learning tasks, such as playing video games. In this study, we applied this mechanism to the generation of handwritten characters. As a starting point, we utilized the tutorial example code provided with the NEST simulator (available on the NEST simulator website) for the generation of the handwritten word "chaos". However, this model lacks flexibility, since it only learns to represent that particular word (there is no decomposition into letters), without lifting the pen (so, one single continuous stroke), and without style variations (one of the main characteristics of real handwriting). Thus, we have improved the original model in two aspects.

Firstly, we have extended this model to learn a set of characters of different alphabets. Because the original NEST implementation generates only one continuous stroke, we have introduced a third output variable, namely the pen-lift channel, to control pen-up or pen-down. This modification allows the simulation of lifting the pen, enabling the model to move to a new location without writing a stroke. This modification is crucial to allow the generation of multi-stroke characters (e.g. characters that require more than one stroke, such as “t” or “A”). 

Secondly, we have adapted the NEST code to generate any number of variations of a single character, thereby imitating the natural variability observed in human handwriting, where no character is identically reproduced across repeated trials. 

Thanks to these improvements, our model can produce variations of multi-stroke handwritten characters, paving the way to the generation of realistic handwritten text. Notably, we relied on one single training example, showing a great advantage compared to the thousands of examples required by deep learning models.