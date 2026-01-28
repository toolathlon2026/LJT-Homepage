---
title: "Composing Parameter‑Efficient Modules with Arithmetic Operations"
collection: publications
category: conferences
permalink: /publication/2023-12-02-parameter-efficient-modules
excerpt: 'We propose a method to compose parameter‑efficient adaptation modules using arithmetic operations, enabling efficient and flexible model adaptation.'
date: 2023-12-02
venue: 'Advances in Neural Information Processing Systems 36 (NeurIPS 2023)'
paperurl: 'https://openreview.net/forum?id=12346'
citation: 'Jinghan Zhang, Shiqi Chen, Junteng Liu, Junxian He. (2023). Composing Parameter‑Efficient Modules with Arithmetic Operations. In Advances in Neural Information Processing Systems 36 (NeurIPS 2023).'
---

Parameter‑efficient fine‑tuning (PEFT) methods, such as adapters and LoRA, have become popular for adapting large pre‑trained models to downstream tasks. However, existing approaches often treat each module independently, limiting their composability and flexibility. This work introduces a novel framework that composes parameter‑efficient modules through arithmetic operations—addition, subtraction, and interpolation—allowing dynamic combination of multiple adaptation signals. We show that composed modules can capture richer task‑specific information while maintaining parameter efficiency. Experiments on a range of NLP benchmarks demonstrate that our composed modules outperform individual PEFT methods and enable new capabilities such as task arithmetic and incremental learning.