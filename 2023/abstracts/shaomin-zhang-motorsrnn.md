# MotorSRNN: A Brain-Inspired Spiking Recurrent Neural Network for Accuracy-Energy-Balanced Cortical Spike Train Decoding

**Authors:** Tengjun Liu

**Presentation type:** Poster at [SNUFA 2023 online workshop (7-8 Nov 2023)](https://snufa.net/2023)

## Abstract

Decoding firing rates, compressed from cortical spike trains (CST), has yielded significant progress in invasive brain-machine interfaces (BMI). Theoretically, CST as features are more potent and efficient. By directly decoding CST, spiking neural networks (SNN) exhibit promise for enhancing invasive BMIs due to high compatibility with CST and a low-energy consuming nature. However, whether SNNs can classify CST with applicable performance remains unclear, as previously reported results were limited. In this study, we proposed the motorSRNN, a recurrent SNN topologically inspired by the primate neural motor circuit. By employing motorSRNN in decoding CST collected from the primary motor cortex of two monkeys, it achieved average classification accuracies of 89.44% and 79.87% respectively, advancing the performance of previous reported SNN method in similar CST-decoding tasks, fSNN, by more than 25%. Furthermore, motorSRNN demonstrated superior early-classification capabilities compared to fSNN, GRU, and LSTM. Additionally, it only theoretically consumed around 1/50 energy compared to traditional GRU and LSTM. Finally, motorSRNN offers insights into a possible rationale for the biologically employed topology: to enhance the resilience against Poisson noise from neighboring neurons in the biological brains. In conclusion, the motorSRNN is feasible for low energy-consuming CST decoding, laying the preliminary groundwork for constructing a fully implantable neuromorphic BMI.