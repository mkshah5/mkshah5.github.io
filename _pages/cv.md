---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Engineering, North Carolina State University, 2026 (expected)
* B.S.E. in Electrical and Computer Engineering, B.S. in Computer Science, Duke University, 2021

Research experience
======
* *Compression Algorithms on AI Accelerators*
  * **Timeline:** May 2023-Present
  * **Institution:** North Carolina State University and Argonne National Laboratory
  * **Core Duties:** Developing training and activation data compression algorithms 
tuned for a variety of AI accelerators including SambaNova, 
Cerebras, Graphcore, and Groq 
  * **Supervisors:** Michela Becchi, Franck Cappello, Sheng Di, Xiaodong Yu

* *Huffman Coding on GPU*
  * **Timeline:** Aug 2022-Jun 2023
  * **Institution:** North Carolina State University and Argonne National Laboratory
  * **Core Duties:** Implemented and evaluated pre-computed Huffman codebook 
scheme to offload codebook computation from GPU using CUDA 
speeding up compression up to 5x and improves speed for HDF5 
chunking and MPI communication.  
  * **Supervisors:** Michela Becchi, Franck Cappello, Sheng Di, Xiaodong Yu

* *GPU-based Compression for Quantum Circuit Simulations*
  * **Timeline:** May 2022-May 2023
  * **Institution:** North Carolina State University and Argonne National Laboratory
  * **Core Duties:** Designed a lossy compression framework targeting tensors in 
quantum circuit tensor network-based simulation improving 
compression ratio relative to state-of-the-art compressors up to 10x 
while creating an alternate design that achieves 3-4x higher 
compression with limited impact on throughput  
  * **Supervisors:** Michela Becchi, Franck Cappello, Sheng Di, Xiaodong Yu

* *Accelerating Random Forest Inference on GPU*
  * **Timeline:** Aug 2021-Apr 2022
  * **Institution:** North Carolina State University
  * **Core Duties:** Developed a novel GPU and FPGA memory layout and kernel for 
Random Forest algorithm to accelerate inference time using CUDA, 
achieving nearly 2x speedup over NVIDIA’s cuML library. 
  * **Supervisors:** Michela Becchi

* *Autoencoder for Plant Phosphoproteomics*
  * **Timeline:** May 2021-Aug 2021
  * **Institution:** North Carolina State University
  * **Core Duties:** Optimized an autoencoder coupled with a supervised neural 
network for plant phenotype prediction using phosphoproteomics 
data. Developed a Shannon Entropy model for significant biomarker 
discrimination.  
  * **Supervisors:** Ross Sozzani, Lisa Van Den Broeck

* *Accelerating Semi-Supervised Support Vector Machine on FPGA*
  * **Timeline:** Aug 2020-Dec 2021
  * **Institution:** Duke University
  * **Core Duties:** Using a Xilinx FPGA, wrote a Verilog implementation for hardware 
acceleration of a semi-supervised SVM. Leveraged existing mixed
integer linear programming algorithms to port to FPGA.   
  * **Supervisors:** John Board

* *Image Analysis of Rice Roots*
  * **Timeline:** Sep 2019-May 2021
  * **Institution:** Duke University
  * **Core Duties:** Developed object detection neural networks to identify phenotypic 
variations in roots of rice strains. Assisted in pipelining image 
analysis and image acquisition through cloud computing.    
  * **Supervisors:** Philip Benfey, Isaiah Taylor

* *Machine Learning Model for Biomarker Selection and Cancer Outcomes*
  * **Timeline:** May 2019-Aug 2019
  * **Institution:** University of Central Florida
  * **Core Duties:** Assisted in developing a network-transfer and bipartite graph 
machine learning model to select significant biomarkers and predict 
cancer outcomes given genomics data, evaluated against RF and 
SVM.    
  * **Supervisors:** Wei Zhang

Skills
======
* Programming/Hardware Languages:
  * C/C++
  * Python
  * Verilog
  * Java
* Frameworks/Tools:
  * CUDA
  * PyTorch
  * OpenMP/MPI
  * Scikit/OpenCV
  * Git
  * Vivado/Quartus

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Posters
======
* *Compressing Quantum Circuit Simulation Tensor Data (Best Graduate Poster Finalist)*
  * International Conference for High Performance Computing, Networking, 
Storage, and Analysis (SC 2022)

Awards
======
* ACM SRC Graduate Poster Second Place (2022)
* Provost's Doctoral Fellowship (2021)
* Graduate Merit Award (2021)
* Dean's List-Pratt School of Engineering (x3; 2017-2020)

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!--   
Service and leadership
======
* Currently signed in to 43 different slack teams -->
