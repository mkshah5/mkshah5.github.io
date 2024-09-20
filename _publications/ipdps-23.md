---
title: "GPU-Accelerated Error-Bounded Compression Framework for Quantum Circuit Simulations"
collection: publications
category: conferences
permalink: /publication/ipdps-23
excerpt: 'In this paper, we explore different lossy compression strategies to substantially shrink quantum circuit tensors in the QTensor package (a state-of-the-art tensor network quantum circuit simulator) while ensuring the reconstructed data satisfy the user-needed fidelity.'
date: 2023-07-18
venue: 'Proceedings of IPDPS &apos;23'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3625549.3658662'
citation: 'M. Shah et al., &quot;GPU-Accelerated Error-Bounded Compression Framework for Quantum Circuit Simulations,&quot; 2023 IEEE International Parallel and Distributed Processing Symposium (IPDPS), St. Petersburg, FL, USA, 2023, pp. 757-767, doi: 10.1109/IPDPS54959.2023.00081.'
---

In this paper, we explore different lossy compression strategies to substantially shrink quantum circuit tensors in the QTensor package (a state-of-the-art tensor network quantum circuit simulator) while ensuring the reconstructed data satisfy the user-needed fidelity.Our contribution is fourfold. (1) We propose a series of optimized pre- and post-processing steps to boost the compression ratio of tensors with a very limited performance overhead. (2) We characterize the impact of lossy decompressed data on quantum circuit simulation results, and leverage the analysis to ensure the fidelity of reconstructed data. (3) We propose a configurable compression framework for GPU based on cuSZ and cuSZx, two state-of-the-art GPU-accelerated lossy compressors, to address different use-cases: either prioritizing compression ratios or prioritizing compression speed. (4) We perform a comprehensive evaluation by running 9 state-of-the-art compressors on an NVIDIA A100 GPU based on QTensor-generated tensors of varying sizes. When prioritizing compression ratio, our results show that our strategies can increase the compression ratio nearly 10 times compared to using only cuSZ. When prioritizing throughput, we can perform compression at the comparable speed as cuSZx while achieving 3-4× higher compression ratios. Decompressed tensors can be used in QTensor circuit simulation to yield a final energy result within 1-5% of the true energy value.
