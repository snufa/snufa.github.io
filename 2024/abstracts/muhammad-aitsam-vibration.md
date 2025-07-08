# Vibration Vision: Real-Time Machinery Fault Diagnosis with Event Cameras

**Authors:** Muhammad Aitsam
                           


**Presentation type:** Poster at [SNUFA 2024 online workshop (5-6 Nov 2024)](https://snufa.net/2024)

## Abstract

Vibration-based fault detection plays a vital role in industry by spotting machinery defects and preventing breakdowns. Traditional methods typically depend on continuous data streams from sensors mounted on the equipment, which can be difficult to process in real-time. This paper presents a new approach using event cameras for vibration-based fault detection. Unlike conventional cameras, event cameras capture minute changes in the scene at microsecond intervals, providing major benefits in dynamic environments, such as higher temporal resolution, lower energy consumption, and a wider dynamic range.

We introduce Event-Based Frequency Mapping (EBFM), a method that precisely measures vibration frequencies within the observed area. By normalizing this frequency data, we generate a detailed heatmap that highlights anomalies and faults. The algorithm takes full advantage of the event cameras' high temporal resolution to quickly compute dominant frequencies. Furthermore, our system includes dynamic tracking of regions of interest (ROIs), allowing focused monitoring of specific areas.

We conducted two experiments to evaluate the system under different conditions. The results demonstrated that the EBFM system successfully measured frequencies in varying lighting conditions and identified abnormal machine behavior during faulty operations.