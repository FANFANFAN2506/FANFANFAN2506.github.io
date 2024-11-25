---
title: "SEESys: Online Pose Error Estimation System for Visual SLAM."
collection: publications
permalink: /publication/paper
excerpt: "In this paper, we develop a SLAM system run-time status monitor (RTS monitor) that performs feature collection with minimal overhead, along with a multi-modality attention-based Deep SLAM Error Estimator (DeepSEE) for error estimation. "
date: 2024-11-04
venue: "SENSYS '24: Proceedings of the 22nd ACM Conference on Embedded Networked Sensor Systems"
paperurl: "https://doi.org/10.1145/3666025.3699341"
citation: "Tianyi Hu, Tim Scargill, Fan Yang, Ying Chen, Guohao Lan, and Maria Gorlatova. 2024. SEESys: Online Pose Error Estimation System for Visual SLAM. In Proceedings of the 22nd ACM Conference on Embedded Networked Sensor Systems (SenSys '24). Association for Computing Machinery, New York, NY, USA, 322–335. https://doi.org/10.1145/3666025.3699341"
---

In this work, we introduce SEESys, the first system to provide online pose error estimation for Simultaneous Localization and Mapping (SLAM). Unlike prior offline error estimation approaches, the SEESys framework efficiently collects real-time system features and delivers accurate pose error magnitude estimates with low latency. This enables real-time quality-of-service information for downstream applications. To achieve this goal, we develop a SLAM system run-time status monitor (RTS monitor) that performs feature collection with minimal overhead, along with a multi-modality attention-based Deep SLAM Error Estimator (DeepSEE) for error estimation. We train and evaluate SEESys using both public SLAM benchmarks and a diverse set of synthetic datasets, achieving an RMSE of 0.235 cm of pose error estimation, which is 15.8% lower than the baseline. Additionally, we conduct a case study showcasing SEESys in a real-world scenario, where it is applied to a real-time audio error advisory system for human operators of a SLAM-enabled device. The results demonstrate that SEESys provides error estimates with an average end-to-end latency of 37.3 ms, and the audio error advisory reduces pose tracking error by 25%.

[Download paper here](http://FANFANFAN2506.github.io/files/Sensys24.pdf)

Recommended citation: Tianyi Hu, Tim Scargill, Fan Yang, Ying Chen, Guohao Lan, and Maria Gorlatova. 2024. SEESys: Online Pose Error Estimation System for Visual SLAM. In Proceedings of the 22nd ACM Conference on Embedded Networked Sensor Systems (SenSys '24). Association for Computing Machinery, New York, NY, USA, 322–335. https://doi.org/10.1145/3666025.3699341