---
title: "Optimizing Edge SLAM: Judicious Parameter Settings and Parallelized Map Updates"
authors:
  - Peter Sossalla
  - Johannes Hofer
  - Justus Rischke
  - me
  - Giang T. Nguyen
  - Martin Reisslein
  - Frank H. P. Fitzek
date: 2022-12-04
publication_type: conference
venue:
  name: "IEEE Global Communications Conference"
  short: "GLOBECOM"
doi: 10.1109/GLOBECOM48099.2022.10001128
abstract: |-
  Edge Simultaneous Localization and Mapping (SLAM) retains only the tracking on the mobile device, while offloading the compute-intensive local mapping and loop close to edge computing. Existing Edge SLAM approaches incur relatively high delays for offloading, resulting in high failure probabilities, i.e., low reliability, for commonly used public SLAM datasets. We discovered that two parameters which had not previously been studied in detail, namely the number of features and the number of keyframes that are bundled for a local map update, play a critical role in the offloading delay. Also, previous approaches updated the local map in the mobile device in a serial manner, incurring map update latencies. We study the numbers of features and bundled keyframes in detail and we parallelize the local map update. We find that judicious parameter settings, namely relatively small numbers of features (750 per frame) and bundled keyframes (1, i.e., effectively no bundling), reduce the map update latency to less than half compared to the previously common settings (1000 features per frame and 6 keyframes used for a map update). For a low network latency of 20ms, these judicious parameter settings in conjunction with our parallelized local map updating, reduce the 79% failure rate of the previous Edge SLAM systems down to 2%.
---
