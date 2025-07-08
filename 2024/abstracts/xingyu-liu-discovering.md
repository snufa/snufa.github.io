# Discovering Connectome Patterns of Brain through the Lens of Generative Models

**Authors:** Xingyu Liu, Guozhang Chen
                           
**Presenting author:** Xingyu Liu

**Presentation type:** Flash talk at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

The inherent connectome structure in biological brain serves as an important prior for efficient learning. A network with well organized structure may achieve more efficient learning compared to a poorly organized one. However, the complexity of connectome data makes it hard to study through simple statistical methods. And the mechanism known as “genetic bottleneck” suggests that the storage capacity of genes carrying this hereditary information is very limited, which means that genes cannot encode the connections between every neuron pair explicitly. Thus, there must exist some low-dimensional representation of connectome that controls the generation of connectivity, which may be difficult to find if we only use simple statistical metrics. In this work, we use generative model and GNNs to squeeze out redundant information and reconstruct graphs that closely resemble connectome data. Then we analyze the latent space to discover key features that distinguish between connectome data and random graphs. We find several important directions that have the greatest impact on the differences. What’s more, the modifications along these main directions show a gradual change in the features of the graph.