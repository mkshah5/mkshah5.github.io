---
title: "Accelerating Random Forest Classification on GPU and FPGA"
collection: publications
category: conferences
permalink: /publication/icpp-22
excerpt: 'In this work, we accelerate RF classification on GPU and FPGA.'
date: 2023-01-13
venue: 'Proceedings of ICPP &apos;22'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3545008.3545067'
citation: 'Milan Shah, Reece Neff, Hancheng Wu, Marco Minutoli, Antonino Tumeo, and Michela Becchi. 2023. Accelerating Random Forest Classification on GPU and FPGA. In Proceedings of the 51st International Conference on Parallel Processing (ICPP &apos;22). Association for Computing Machinery, New York, NY, USA, Article 4, 1–11. https://doi.org/10.1145/3545008.3545067'
---

In this work, we accelerate RF classification on GPU and FPGA. In order to provide efficient support for large datasets, we propose a hierarchical memory layout suitable to the GPU/FPGA memory hierarchy. We design three RF classification code variants based on that layout, and we investigate GPU- and FPGA-specific considerations for these kernels. Our experimental evaluation, performed on an Nvidia Xp GPU and on a Xilinx Alveo U250 FPGA accelerator card using publicly available datasets on the scale of millions of samples and tens of features, covers various aspects. First, we evaluate the performance benefits of our hierarchical data structure over the standard compressed sparse row (CSR) format. Second, we compare our GPU implementation with cuML, a machine learning library targeting Nvidia GPUs. Third, we explore the performance/accuracy tradeoff resulting from the use of different tree depths in the RF. Finally, we perform a comparative performance analysis of our GPU and FPGA implementations. Our evaluation shows that, while reporting the best performance on GPU, our code variants outperform the CSR baseline both on GPU and FPGA. For high accuracy targets, our GPU implementation yields a 5-9 × speedup over CSR, and up to a 2 × speedup over Nvidia’s cuML library.
