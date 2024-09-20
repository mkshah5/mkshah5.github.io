---
title: "Lightweight Huffman Coding for Efficient GPU Compression"
collection: publications
category: conferences
permalink: /publication/ics-23
excerpt: 'Our work seeks to reduce the Huffman coding runtime with minimal-to-no impact on cuSZ&apos;s compression efficiency.'
date: 2023-06-21
venue: 'Proceedings of ICS &apos;23'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3577193.3593736'
citation: 'Milan Shah, Xiaodong Yu, Sheng Di, Michela Becchi, and Franck Cappello. 2023. Lightweight Huffman Coding for Efficient GPU Compression. In Proceedings of the 37th ACM International Conference on Supercomputing (ICS &apos;23). Association for Computing Machinery, New York, NY, USA, 99–110. https://doi.org/10.1145/3577193.3593736'
---

Our contributions are as follows. First, we examine a variety of probability distributions to determine which distributions closely model the input to cuSZ's Huffman coding stage. From these distributions, we create a dictionary of pre-computed codebooks such that during compression, a codebook is selected from the dictionary instead of computing a custom codebook. Second, we explore three codebook selection criteria to be applied at runtime. Finally, we evaluate our scheme on real-world datasets and in the context of two important application use cases, HDF5 and MPI, using an NVIDIA A100 GPU. Our evaluation shows that our method can reduce the Huffman coding penalty by a factor of 78--92×, translating to a total speedup of up to 5× over baseline cuSZ. Smaller HDF5 chunk sizes enjoy over an 8× speedup in compression and MPI messages on the scale of tens of MB have a 1.4--30.5× speedup in communication time.
