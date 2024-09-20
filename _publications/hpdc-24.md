---
title: "A Portable, Fast, DCT-based Compressor for AI Accelerators"
collection: publications
category: conferences
permalink: /publication/hpdc-24
excerpt: 'In this paper, we propose a novel, portable, DCT-based lossy compressor that can be used across a variety of AI accelerators.'
date: 2024-08-30
venue: 'Proceedings of HPDC &apos;24'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3625549.3658662'
citation: 'Milan Shah, Xiaodong Yu, Sheng Di, Michela Becchi, and Franck Cappello. 2024. A Portable, Fast, DCT-based Compressor for AI Accelerators. In Proceedings of the 33rd International Symposium on High-Performance Parallel and Distributed Computing (HPDC &apos;24). Association for Computing Machinery, New York, NY, USA, 109–121. https://doi.org/10.1145/3625549.3658662'
---

In this paper, we propose a novel, portable, DCT-based lossy compressor that can be used across a variety of AI accelerators. More specifically, we make the following contributions: 1. We propose a DCT-based lossy compressor design for training data that uses operators supported across four state-of-the-art AI accelerators: Cerebras CS-2, SambaNova SN30, Groq GroqChip, and Graphcore IPU. 2. We design two optimization techniques to allow for higher resolution compressed data on certain platforms and improved compression ratio on the IPU. 3. We evaluate our compressor's ability to preserve accuracy on four benchmarks, three of which are AI for science benchmarks going beyond image classification. Our experiments show that accuracy degradation can be limited to 3% or less, and sometimes, compression improves accuracy. 4. We study compression/decompression time as a function of resolution and batch size, finding that our compressor can achieve throughputs on the scale of tens of GB/s, depending on the platform.
