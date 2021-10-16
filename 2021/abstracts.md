# List of SNUFA2021 abstracts

[Back to meeting overview](.)

## Deriving local synaptic learning rules for efficient representations in networks of spiking neurons 
Viola Priesemann, Lucas Rudelt, Fabian Mikulasch <br/>
<sub>Presentation: talk </sub>

**Abstract:** How can neural networks learn to efficiently represent complex and high-dimensional inputs via local plasticity mechanisms? Classical models of representation learning assume that input weights are learned via pairwise Hebbian-like plasticity. Here, we show that pairwise Hebbian-like plasticity only works under specific requirements on neural dynamics and input statistics. To overcome these limitations, we derive from first principles a learning scheme based on voltage-dependent synaptic plasticity rules. Here, inhibition learns to locally balance excitatory input in individual dendritic compartments, and thereby can modulate excitatory synaptic plasticity to learn efficient representations. We demonstrate in simulations that this learning scheme works robustly even for complex, high-dimensional and correlated inputs. It also works in the presence of inhibitory transmission delays, where Hebbian-like plasticity typically fails. Our results draw a direct connection between dendritic excitatory-inhibitory balance and voltage-dependent synaptic plasticity as observed in vivo, and suggest that both are crucial for representation learning. 


## Spike-based embeddings for multi-relational graph data 
Dominik Dold, Josep Soler Garrido, Victor Caceres Chian, Marcel Hildebrandt, Thomas Runkler <br/>
<sub>Presentation: talk </sub>

**Abstract:** A rich data representation that finds wide application in industry and research is the so-called knowledge graph - a graph-based structure where entities are depicted as nodes and relations between them as edges. Complex systems like molecules, social networks and industrial factory systems can be described using the common language of knowledge graphs, allowing the usage of graph embedding algorithms to make context-aware predictions in these information-packed environments.

Although graphs are a flexible and powerful modelling tool, only little work exists on applying spiking neural networks to graph-structured data, e.g., spike-based  versions  of  classical  graph algorithms like finding shortest paths, minimum spanning trees and maximum flows have been recently proposed. We extend this work to knowledge graphs by introducing a  spike-based  algorithm  where  nodes  in  a  graph  are represented  by  single  spike  times  of  neuron  populations  and relations as spike time differences between populations. Learning such  spike-based  embeddings  only  requires  knowledge  about spike times and spike time differences, compatible with recently proposed frameworks for training spiking neural networks. We further extend this coding scheme to deep architectures, i.e., spiking graph neural networks, introducing a novel, event-based and highly sparse knowledge graph embedding algorithm.

In particular, this approach can be used to learn spike-based representations of data structures that have no obvious or natural representation as spikes, e.g., social networks and tabular data, but can be modelled as knowledge graphs. Not only can such spike representations be directly used for inference on the underlying graph, but also as input to other spiking neural networks. Thus, we are convinced that our work constitutes an important step towards enabling a modular synthesis of spike-based machine learning methods and graph embedding algorithms, unlocking the potential of joining event-based computing and symbolic data to build powerful and energy efficient artificial intelligence applications and reasoning systems.


## Training Delays in Spiking Neural Networks 
Pau Vilimelis Aceituno <br/>
<sub>Presentation: poster </sub>

**Abstract:** Biological spiking neural networks (SNNs) are known to encode information in the precise timing of spikes. However, most machine learning methods can only work on rate-like variables, restricting the applications of SNNs.
In this work we present a method to train synaptic delays in single layer SNNs through an algebraic approach. In our method, spike times are converted to complex numbers and the associated complex weights are found by linear algebra. The synaptic parameters -- both weights and delays -- are then obtained by converting complex numbers back into weights and delays. 
We will present the theoretical foundations of our approach, showing how it is mathematically equivalent to a linear regression/classification on time-unrolled variables compressed in the Fourier domain (State & Vilimelis, ICANN, 2019). We will also present on event-based touch localization inspired by the sand scorpion (Haessig et al., Front. Neurosci.,  2020).
While the use of complex numbers to encode delays is not new (Frady & Sommer, PNAS, 2019), its formulation in terms of linear algebra without any calculus provides a different angle with new mathematical intuitions and computationally efficient learning. 


## StereoSpike: Depth Learning with a Spiking Neural Network 
Ulysse Rancon, Javier Cuadrado-Anibarro, Benoit Cottereau, Timothée Masquelier <br/>
<sub>Presentation: talk </sub>

**Abstract:** Depth estimation is an important computer vision task, useful in particular for navigation in autonomous vehicles, or for object manipulation in robotics. Here we solved it using an end-to-end neuromorphic approach, combining two event-based cameras and a Spiking Neural Network (SNN) with a slightly modified  U-Net-like encoder-decoder architecture, that we named StereoSpike. More specifically, we used the Multi Vehicle Stereo Event Camera Dataset (MVSEC). It provides a depth ground-truth, which was used to train StereoSpike in a supervised  manner, using surrogate gradient descent. We propose a novel readout paradigm to obtain a dense analog prediction –the depth of each pixel– from the spikes of the decoder. We demonstrate that this architecture generalizes very well, even better than its non-spiking counterparts, leading to state-of-the-art test accuracy. To the best of our knowledge, it is the first time that such a large-scale regression problem is solved by a fully spiking network. Finally, we show that low firing rates (<10%) can be obtained via regularization, with a minimal cost in accuracy. This means that StereoSpike could be implemented efficiently on neuromorphic chips, opening the door for low power real time embedded systems.


## Efficient GPU training of SNNs using approximate RTRL 
James Knight, Thomas Nowotny <br/>
<sub>Presentation: talk </sub>

**Abstract:** Last year’s SNUFA workshop report concluded “Moving toward neuron numbers comparable with biology and applying these networks to real-world data-sets will require the development of novel algorithms, software libraries, and dedicated hardware accelerators that perform well with the specifics of spiking neural networks” [1]. Taking inspiration from machine learning libraries — where techniques such as parallel batch training minimise latency and maximise GPU occupancy — as well as our previous research on efficiently simulating SNNs on GPUs for computational neuroscience [2,3], we are extending our GeNN SNN simulator to pursue this vision. To explore GeNN's potential, we use the eProp learning rule [4] — which approximates RTRL — to train SNN classifiers on the Spiking Heidelberg Digits and the Spiking Sequential MNIST datasets. We find that the performance of these classifiers is comparable to those trained using BPTT [5] and verify that the theoretical advantages of neuron models with adaptation dynamics [5] translate to improved classification performance. We then measured execution times and found that training an SNN classifier using GeNN and eProp becomes faster than SpyTorch and BPTT after less than 685 timesteps and much larger models can be trained on the same GPU when using GeNN. Furthermore, we demonstrate that our implementation of parallel batch training improves training performance by over 4⨉ and enables near-perfect scaling across multiple GPUs. Finally, we show that performing inference using a recurrent SNN using GeNN uses less energy and has lower latency than a comparable LSTM simulated with TensorFlow [6] .

References
1. Zenke et al. (2021). 10.1016/j.neuron.2021.01.009
2. Knight et al. (2021). 10.1038/s43588-020-00022-7
3. Knight et al. (2018). 10.3389/fnins.2018.00941
4. Bellec et al. (2020). 10.1038/s41467-020-17236-y
5. Zenke et al. (2021). 10.1109/JPROC.2020.3045625
6. Plank et al. (2021). arXiv 2107.03992




## Predictive Plasticity: Anticipation of spike patterns at the single neuron level and the emergence of spike-timing-dependent plasticity 
Matteo Saponati, Martin Vinck <br/>
<sub>Presentation: poster </sub>

**Abstract:** The anticipation of future events to guide behavior is a hallmark of living systems. Yet, the learning rules that enable neurons to predict and fire ahead of inputs are still unknown. Here we propose a plasticity rule based on predictive processing. The neuron learns a low-rank model of the dynamics of the input in its membrane potential. We derive the predictive learning rule as a solution to an optimization problem and we show how it can be implemented at the single neuron level with only local information. The membrane potential is the key variable for the optimization process, whereas the post-synaptic firing is a hidden variable which constrains the voltage and guides the anticipation of predictable sequences. Accordingly, the neuron amplifies the synapses which maximally predict other synaptic inputs based on their temporal relations. The learning rule recapitulates several spike-timing-dependent plasticity (STDP) mechanisms observed experimentally. Moreover, we show that neurons can learn sequences over long timescales and fire for the first inputs in a sequence. The proposed learning rule can explain the development of anticipatory signaling of motion in the visual system. In sum, we developed a novel learning rule that produces STDP as an emergent property and gives rise to the anticipation of input sequences. This suggests prediction as a guiding principle to orchestrate learning in single neurons.   


## Event-based Backpropagation for Exact Gradients in Spiking Neural Networks 
Christian Pehle, Timo Wunderlich <br/>
<sub>Presentation: talk </sub>

**Abstract:** Gradient-based optimization powered by the backpropagation algorithm proved to be the pivotal method in the training of non-spiking artificial neural networks. At the same time, spiking neural networks hold the promise for efficient processing of real-world sensory data by communicating using discrete events in continuous time. We derive the backpropagation algorithm for a recurrent network of spiking (leaky integrate-and-fire) neurons with hard thresholds and show that the backward dynamics amount to an event-based backpropagation of errors through time. Our derivation uses the jump conditions for partial derivatives at state discontinuities found by applying the implicit function theorem, allowing us to avoid approximations or substitutions. We find that the gradient exists and is finite almost everywhere in weight space, up to the null set where a membrane potential is precisely tangent to the threshold. Our presented algorithm, EventProp, computes the exact gradient with respect to a general loss function based on spike times and membrane potentials. Crucially, the algorithm allows for an event-based communication scheme in the backward phase, retaining the potential advantages of temporal sparsity afforded by spiking neural networks. We demonstrate the optimization of spiking networks using gradients computed via EventProp and the Yin-Yang and MNIST datasets with either a spike time-based or voltage-based loss function and report competitive performance. Our work supports the rigorous study of gradient-based optimization in spiking neural networks as well as the development of event-based neuromorphic architectures for the efficient training of spiking neural networks. While we consider the leaky integrate-and-fire model in this work, our methodology generalises to any neuron model defined as a hybrid dynamical system.


## Spiking networks grown and functionalized by noisy waves 
Guruprasad Raghavan, Cong Lin, Matt Thomson <br/>
<sub>Presentation: poster </sub>

**Abstract:** Living  neural  networks  in  our  brains  autonomously  self-organize  into large,  complex  architectures  during  early  development. A key mechanism that enables the formation and learning of complex organized architectures in the brain is the emergence of traveling spatio-temporal waves of neuronal activity across the brain. Previous studies have demonstrated that neuronal waves provide a mechanism to self-organize retinotopic pooling architectures in networks that are subject to growth and noisy stimulus. Here, we  examine  the  potential  role  of neuronal  waves  in  internalizing  dynamic  learning  representations  by  using  a  phased learning strategy; which involves:  (i) passive (unsupervised) observation to internalize  inputs  via  self-organization  in  the  latent  space,  followed  by  (ii)  learning mappings between the resulting neuronal dynamics of the hidden layer to provided  categorical labels. To  achieve  this,  we  propose  a  modular  dynamical  systems  tool-kit  that  can  be seamlessly stacked to allow for self-organization and phased learning across multiple layers of the  spiking  network. Furthermore,  inter-layer  weights  can  be  trained  via  local (gradient-informed)  feedback  rules,  in  the  fashion  of  a  closed-loop  control  system for real-time learning.  We demonstrate that networks endowed with spatio-temporal neuronal dynamics are especially suited for representing dynamic input data,  like the continuous rotation of MNIST digits or dynamic gesture detection datasets. Broadly, our work shows that the dynamical systems framework for learning can be used to self-organize large computational devices.


## Understanding the role of neural heterogeneity in learning 
Nicolas Perez-Nieves, Vincent C. H. Leung, Pier Luigi Dragotti, Dan F. M. Goodman <br/>
<sub>Presentation: talk </sub>

**Abstract:** The brain has a hugely diverse and heterogeneous nature. The exact role of heterogeneity has been relatively little explored as most neural models tend to be largely homogeneous. We trained spiking neural networks with varying degrees of heterogeneity on complex real-world tasks and found that heterogeneity resulted in more stable and robust training and improved training performance, especially for tasks with a higher temporal structure. Moreover, the optimal distribution of parameters found by training was found to be similar to experimental observations. These findings suggest that heterogeneity is not simply a result of noisy biological processes, but it may play a crucial role for learning in complex, changing environments. 


## Deep Residual Learning in Spiking Neural Networks 
Wei Fang <br/>
<sub>Presentation: poster </sub>

**Abstract:** Deep Spiking Neural Networks (SNNs) present optimization difficulties for gradient-based approaches due to discrete binary activation and complex spatial-temporal dynamics.  Considering the huge success of ResNet in deep learning, it would be natural to train deep SNNs with residual learning. Previous Spiking ResNet mimics the standard residual block in ANNs and simply replaces ReLU activation layers with spiking neurons, which suffers the degradation problem and can hardly implement residual learning. In this paper, we propose the spike-element-wise (SEW) ResNet to realize residual learning in deep SNNs. We prove that the SEW ResNet can easily implement identity mapping and overcome the vanishing/exploding gradient problems of Spiking ResNet. We evaluate our SEW ResNet on ImageNet and DVS Gesture datasets, and show that SEW ResNet outperforms the state-of-the-art directly trained SNNs in both accuracy and time-steps.  Moreover, SEW ResNet can achieve higher performance by simply adding more layers, providing a simple method to train deep SNNs. To our best knowledge, this is the first time that directly training deep SNNs with more than 100 layers becomes possible.


## Optimizing for fast sampling-based inference yields oscillatory dynamics in a spiking model of primary visual cortex 
Zhen Chen <br/>
<sub>Presentation: poster </sub>

**Abstract:** The neural sampling hypothesis suggests that the brain’s sensory processing can be understood as implementing a sampling process that computes the posterior belief over latent variables given a sensory observation. Prior studies have examined this hypothesis in the context of the primary visual cortex (V1), and almost all of them have assumed V1 neurons to represent the continuous intensity of Gabor- shaped features either by firing rates or membrane potentials (Hoyer and Hyvärinen, 2003; Haefner et al., 2016; Orbán et al., 2016; Bányai et al., 2017). All of these models either implemented known sampling algorithms or simply ignored dynamics. Most recently, Echeveste et al. 2020 showed that a rate-based model optimized for fast sampling exhibited rich dynamics including marked stimulus-dependent transient responses and gamma oscillations.

It remains unclear whether these dynamic features observed in models of continuous variables would still emerge in the case of binary latents. However, learning in Gaussian binary models of natural images also gives rise to Gabor-shaped receptive fields (Bornschein et al., 2013). Gibbs-sampling based inference in binary models has been shown to be feasible using spiking networks (Buesing et al., 2011; Pecevski, et al., 2011) and using leaky integrate-and-fire neurons (Chattoraj et al., 2019), which yielded near contrast-invariant tuning curves and realistic spiking statistics, interpretable as probabilistic population codes (PPCs, Shivkumar et al., 2018).

Here, we optimized the recurrent connectivity of small networks consisting of binary excitatory and inhibitory neurons  that obey Dale’s Law to maximize the speed of sampling-based inference in a generative model of retinal images. We found sampling was fastest for non-symmetric connectivity structures that implied oscillatory dynamics (Hennequin et al., 2014) with performance between Gibbs sampling and independent sampling. Importantly, unlike Gibbs sampling and independent sampling, neural responses in our network presented strong oscillations, as observed in the cortex.


## A Biologically Plausible Learning Rule Based on the Information Bottleneck 
Kyle Daruwalla, Mikko Lipasti <br/>
<sub>Presentation: poster </sub>

**Abstract:** Artificial neural networks have successfully tackled a large variety of problems by training extremely deep networks via back-propagation. A direct application of back-propagation to spiking neural networks contains biologically implausible components, like the weight transport problem or separate inference and learning phases. Various methods address different components individually, but a complete solution remains intangible. Here, we take an alternate approach that avoids back-propagation and its associated issues entirely. Recent work in deep learning proposed independently training each layer of a network via the information bottleneck (IB). Subsequent studies noted that this layer-wise approach circumvents error propagation across layers, leading to a biologically plausible paradigm. Unfortunately, the IB is computed using a batch of samples. The prior work addresses this with a weight update that only uses two samples (the current and previous sample). Our work takes a different approach by decomposing the weight update into a local and global component. The local component is Hebbian and only depends on the current sample. With the appropriate neuron model, the local component can be expressed as an STDP-like update. The global component computes a layer-wise modulatory signal that depends on a batch of samples. We show that this modulatory signal can be learned by an auxiliary circuit with working memory (WM) like a reservoir. Thus, we can use batch sizes greater than two, and the batch size determines the required capacity of the WM. To the best of our knowledge, our rule is the first biologically plausible mechanism to directly couple synaptic updates with a WM of the task. We evaluate our rule on synthetic datasets and image classification datasets like MNIST, and we explore the effect of the WM capacity on learning performance. We hope our work is a first-step towards understanding the mechanistic role of memory in learning.


## Simulating Pushdown Automata with Noisy Spiking Neural Networks 
Tom Burns <br/>
<sub>Presentation: poster </sub>

**Abstract:** An oft-cited set of proofs demonstrating the computational power of spiking neural networks (SNNs) is from Maass (1996), which demonstrates the ability of SNNs to simulate arbitrary Turing machines (TMs). We identify a linearity assumption in the post-synaptic response functions of neurons in this work and an assumption that the system is noiseless which allows the infinite tape required for simulating a TM. Removing the linearity assumption in the post-synaptic response functions and permitting some noise destroys this ability, however we are developing modifications which enable the simulation of finite pushdown automata which operate like TMs. This suggests the computational power of SNNs of a more general and biologically-plausible kind may have a lower bound of finite pushdown automata.


## Optimal initialization strategies for Deep Spiking Neural Networks 
Julia Gygax, Julian Rossbroich, Manvi Agarwal, Friedemann Zenke <br/>
<sub>Presentation: talk </sub>

**Abstract:** Recent advances in neuromorphic hardware and Surrogate Gradient (SG) learning highlight the potential of Spiking Neural Networks (SNNs) for energy-efficient signal processing and learning. Like in Artificial Neural Networks (ANNs), training performance in SNNs strongly depends on the initialization of synaptic and neuronal parameters. While there are established methods of initializing deep ANNs for high performance, effective strategies for optimal SNN initialization are lacking. Here, we address this gap and propose flexible data-dependent initialization strategies for SNNs. 

We hypothesized that the fluctuation-driven firing regime, commonly observed in neurobiology, could provide a suitable initialization for SNNs. To test this theory, we derived data-dependent scaling laws that link the afferent weight distribution of individual neurons to expected membrane potential fluctuations at initialization. We empirically show that networks initialized with these scaling laws exhibit overall better performance after subsequent training than networks that were not initialized in the fluctuation-driven regime. Further analysis revealed that the best training performance is achieved by initializations in the fluctuation-driven regime while also keeping the absolute value of the weights small. These findings generalized across several different datasets and across various SNN architectures, including shallow SNNs, deep convolutional, and recurrent SNNs that satisfy Dale’s law. In the latter case, we tuned excitatory and inhibitory weight distributions, such that input currents canceled each other on average, leading to an approximate excitation-inhibition (EI) balance. Since optimal weight initialization is firing rate dependent, we further explored active initialization strategies inspired by homeostatic plasticity in the brain. Specifically, we show that activity-dependent homeostatic weight regularization broadens the parameter regime of good initializations.

In summary, we provide easy-to-implement initialization strategies based on fluctuation-driven firing that facilitate the training of high-performance SNNs. Finally, our work suggests that EI-balance constitutes a good initial state for future learning and that homeostatic plasticity can compensate to some extent for suboptimal initializations.


## Spiking neural networks trained via proxy 
Saeed Reza Kheradpisheh, Maryam Mirsadeghi, Timothee Masquelier <br/>
<sub>Presentation: poster </sub>

**Abstract:** We propose a new learning algorithm to train spiking neural networks (SNN) using conventional artificial neural networks (ANN) as proxy. We couple two SNN and ANN networks, respectively, made of integrate-and-fire (IF) and ReLU neurons with the same network architectures and shared synaptic weights. The forward passes of the two networks are totally independent. By assuming IF neuron with rate-coding as an approximation of ReLU, we backpropagate the error of the SNN in the proxy ANN to update the shared weights, simply by replacing the ANN final output with that of the SNN. We applied the proposed proxy learning to deep convolutional SNNs and evaluated it on two benchmarked datasets of Fashion-MNIST and Cifar10 with 94.56% and 93.11% classification accuracy, respectively. The proposed networks could outperform other deep SNNs trained with tandem learning, surrogate gradient learning, or converted from deep ANNs. Converted SNNs require long simulation times to reach reasonable accuracies while our proxy learning leads to efficient SNNs with much smaller simulation times. 


## Norse: A library for gradient-based learning in Spiking Neural Networks 
Jens Egholm Pedersen, Christian Pehle <br/>
<sub>Presentation: talk </sub>

**Abstract:** We introduce Norse: An open-source library for gradient-based training of spiking neural networks. In contrast to neuron simulators which mainly target computational neuroscientists, our library seamlessly integrates with the existing PyTorch ecosystem using abstractions familiar to the machine learning community. This has immediate benefits in that it provides a familiar interface, hardware accelerator support and, most importantly, the ability to use gradient-based optimization. While many parallel efforts in this direction exist, Norse emphasizes flexibility and usability in three ways. Users can conveniently specify feed-forward (convolutional) architectures, as well as arbitrarily connected recurrent networks. We strictly adhere to a functional and class-based API such that neuron primitives and, for example, plasticity rules composes. Finally, the functional core API ensures compatibility with the PyTorch JIT and ONNX infrastructure. We have made progress to support network execution on the SpiNNaker platform and plan to support other neuromorphic architectures in the future. While the library is useful in its present state, it also has limitations we will address in ongoing work. In particular, we aim to implement event-based gradient computation, using the EventProp algorithm, which will allow us to support sparse event-based data efficiently, as well as work towards support of more complex neuron models. With this library, we hope to contribute to a joint future of computational neuroscience and neuromorphic computing.


## Modelling the effect of dopamine on E-I balance in spiking neural networks 
Ildefonso Ferreira Pica <br/>
<sub>Presentation: poster </sub>

**Abstract:** Neural network models provide a useful tool to study brain dynamics, and understand relevant mechanisms for cognition. A key point of these models is to explain the irregularity of the spiking activity of neurons that is observed in vivo. To get irregular activity without relying on stochastic inputs, large fluctuations of the network dynamics need to be counterbalanced by weak synaptic weights and a balance in excitatory and inhibitory activity. This E-I balance results in complex and irregular spiking activity because the average activity of neuron are kept below a threshold, which then allows for fluctuations in the input to cause reactive spiking activity. This setup is efficient, as it moderates high firing activity, and it allows for non-linear processing of stimuli because the network of neurons can generate complex patterns of activity. The neuromodulator dopamine is known to modulate the E-I balance. Here I will present some simulation results where we have modelled the modulatory effect of dopamine in E-I balanced spiking neural networks, by lowering the action potential (AP) threshold in the inhibitory leaky integrate and fire neurons. The act of lowering the AP threshold, can induce a shift from a regular  firing regime to an irregular firing regime which may support more complex computations.


[Back to meeting overview](.)


