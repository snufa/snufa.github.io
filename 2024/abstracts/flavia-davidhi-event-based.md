# Event-based seizure detection in iEEG using neuromorphic processing

**Authors:** Flavia Davidhi, Filippo Costa, Debora Ledergerber, Giacomo Indiveri, Lukas Imbach, Johannes Sarnthein
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Epilepsy is a neurological disorder that affects approximately 1% of the global population. The current method for seizure monitoring, seizure diaries, is often inaccurate, posing challenges for precise monitoring. This study presents a novel approach for seizure detection using neuromorphic hardware. We analysed intracranial EEG (iEEG) data in the high-frequency (>250 Hz) low-voltage fast activity (LVFA) band and conducted spectral analysis to detect seizure onset patterns. We performed signal compression and event-based encoding through Asynchronous Delta Modulation (ADM). ADM thresholds were set using the mean and 5× standard deviation of the first 2 seconds of the seizure signal. Analysis of the bipolar seizure onset channel in one patient revealed descending frequency patterns (chirps) at the onset of all 26 recorded seizures. We designed a spiking neural network to detect seizure-related patterns, including chirps, with a control mechanism that adjusts network activity based on the LVFA band. This network was implemented on neuromorphic hardware, allowing for the detection of one of the observed chirps. This represents a first step towards event-based seizure detection.