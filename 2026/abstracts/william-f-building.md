# Building and interpreting spiking network dynamics via sliding-mode control

**Authors:** William F. Podlaski, Christian K. Machens
                           
**Presenting author:** William F. Podlaski

**Presentation type:** Flash talk at [SNUFA 2026 online workshop (4-5 Nov 2026)](https://snufa.net/2026)

## Abstract

The non-smooth, discontinuous nature of action potentials has long posed a challenge for embedding interpretable dynamics into recurrent spiking neural networks. Typically, this problem is circumvented by smoothing over the threshold nonlinearities—either by relaxing spikes into continuous rate dynamics or employing surrogate gradients for learning—effectively removing the hard-spiking regime. Here, we propose an alternative theoretical framework grounded in control theory. We consider low-rank integrate-and-fire networks where spiking activity is localized to a low-dimensional latent space, allowing us to directly visualize how hard spiking nonlinearities shape network dynamics. To achieve analytical tractability without smoothing, we examine networks with lateral inhibitory connectivity in the limit of shrinking synaptic connections. In this limit, latent trajectories are constrained to spike-threshold boundaries, directly mapping the system onto the mathematics of piecewise-smooth dynamical systems and Filippov sliding surfaces. This connection provides simple, closed-form fitting procedures to build target dynamics—such as attractors and limit cycles—directly into spiking networks. Furthermore, we show how this framework scales to high-dimensional systems, where sliding dynamics along the edges and vertices of latent convex polytopes give rise to structured cell-assembly dynamics. Overall, this sliding-mode perspective provides a tractable, interpretable blueprint for computing directly with spikes without rate approximations, with broad implications for computational neuroscience and neuromorphic engineering.