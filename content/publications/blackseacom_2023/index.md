---
title: "Estimating Link Capacity with Uncertainty Bounds in Cellular Networks"
authors:
  - Christian L. Vielhaus
  - Osel Lhamo
  - me
  - Justus Rischke
  - Vincent Latzko
  - Sandra Zimmermann
  - Peter Sossalla
  - Daniel F. Külzer
  - Frank H. P. Fitzek
date: 2023-07-04
publication_type: conference
venue:
  name: "IEEE International Black Sea Conference on Communications and Networking"
  short: "BlackSeaCom"
doi: 10.1109/BlackSeaCom58138.2023.10299770
abstract: |-
  Machine learning (ML) equips next-generation networks with anticipatory capabilities. End-to-end predictive Quality of Service (pQoS) leverages ML models to estimate QoS indicators. In this paper, we present several ML models that can estimate the maximum achievable instantaneous throughput (link capacity) of cellular networks. The models do not only estimate the most likely value, but also quantify the uncertainty of their own estimate by providing estimated quantile values as uncertainty bounds. These estimates with uncertainty bounds enable network functions and user applications to make adaptive decisions that take the QoS into account. We validate the estimation performance of our ML models on a dataset captured in a real cellular network. Furthermore, we discuss what kind of information is required and how much data is sufficient to reach high estimation accuracy. We demonstrate that with a mixture of information from users and base stations a mean absolute error of less than 3 Mbit/s in downlink and 1 Mbit/s in uplink can be achieved. At the same time, the uncertainty bounds accurately predict the quantile values with quantile loss values below 1 Mbit/s. Moreover, we evaluate the estimation performance per cell for models using different training schemes. Our findings suggest that cells exhibit diverse characteristics that result in varying estimation accuracies. Models may perform poorly on cells they have not been trained on, because of the diverse data distributions of each cell. We find that cell-based models trained specifically for individual cells yield the best results although they are trained with the smallest datasets.
---
