# Decoding Finger Velocity from Cortical Spike Trains with Recurrent Spiking Neural Networks

**Authors:** Tengjun Liu*, Julia Gygax*, Julian Rossbroich*, Yansong Chua, Shaomin Zhang, Friedemann Zenke
                           
**Presenting author:** Tengjun Liu

**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Invasive cortical brain-machine interfaces (BMIs) can significantly improve the life quality of motor-impaired patients. Nonetheless, externally mounted pedestals pose an infection risk, which calls for fully implanted systems. Such systems, however, must meet strict latency and energy constraints while providing reliable decoding performance. While recurrent spiking neural networks (RSNNs) are ideally suited for ultra-low-power, low-latency processing on neuromorphic hardware, it is unclear whether they meet the above requirements. To address this question, we trained RSNNs to decode finger velocity from cortical spike trains (CSTs) of two macaque monkeys. First, we found that a large RSNN model outperformed existing feed-forward spiking neural networks (SNNs) and artificial neural networks (ANNs) in terms of their decoding accuracy. We next developed a tiny RSNN with a smaller memory footprint, low firing rates, and sparse connectivity. Despite its reduced computational requirements, the resulting model performed substantially better than existing SNN and ANN decoders. Our results thus demonstrate that RSNNs offer competitive CST decoding performance under tight resource constraints and are promising candidates for fully implanted ultra-low-power BMIs with the potential to revolutionize patient care.