---
title: "In‑Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation"
collection: publications
category: conferences
permalink: /publication/2024-07-01-sharpness-alerts
excerpt: 'We propose using in‑context sharpness of inner representations as an early‑warning signal for hallucination in language models.'
date: 2024-07-01
venue: 'Proceedings of the 41st International Conference on Machine Learning (ICML)'
paperurl: 'https://proceedings.mlr.press/v202/chen23s.html'
citation: 'Shiqi Chen, Miao Xiong, Junteng Liu, Zhengxuan Wu, Teng Xiao, Siyang Gao, Junxian He. (2024). In‑Context Sharpness as Alerts: An Inner Representation Perspective for Hallucination Mitigation. In Proceedings of the 41st International Conference on Machine Learning (ICML).'
---

Hallucination remains a major challenge for large language models (LLMs). This paper introduces a novel detection and mitigation approach based on the sharpness of inner representations during in‑context learning. We observe that the sharpness of certain hidden states correlates strongly with the likelihood of hallucination. By monitoring this sharpness in real‑time, we can flag potentially unreliable model outputs and apply corrective measures. Experiments across multiple hallucination benchmarks show that our method significantly reduces hallucination rates without compromising overall model performance. The findings offer a new perspective on leveraging internal model dynamics for improved reliability.