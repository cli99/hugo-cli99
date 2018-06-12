+++
# Date this page was created.
date = "2017-08-30"

# Project title.
title = "MLModelScope (CarML)"

# Project summary to display on homepage.
summary = "An open-source batteries-included platform for performing evaluations on ML/DL algorithms across datasets, frameworks, and systems to analyze accuracy, efficiency, and performance."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "carml.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["current"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ":smile:"

+++

The current landscape of Machine Learning (ML) is fragmented. Many hardware companies and software stacks are proposing diverse hardware architectures and software paradigms. While this is good for innovation, it does make analyzing the different ML offering complicated and error-prone. We propose MLModelScope, a batteries-included platform for performing evaluations on ML/DL algorithms across datasets, frameworks, and systems to analyze accuracy, efficiency, and performance. 

MLModelScope (CarML) allows one to dissect ML models and characterize performance through a common interface, generating a report as a byproduct. By simplifying and standardizing the analysis and evaluation of ML offerings, we enable people from industry and researchers to have a common methodology and platform by which to compare the offerings and ideas.

MLModelScope currently has the following capabilities:

1. Model accuracy replication and verification 
2. 170 built-in models in Caffe, Caffe2, CNTK, MXNet, Tensorfow, and TensorRT
3. Supports X86, ARM, and PPC
4. Runs on Volta, Pascal, Maxwell, Kepler, and Jetson TX1 and TX2
5. Top1/Top5 accuracy on popular datasets such as ImageNet, CIFAR, MNIST
6. Model divergence Analysis for a given input
7. End-To-End profiling
8. Model layer and GPU kernel information on timing, hardware performance counter, and
9. CUDA execution profile
10. Static profiling such as theoretical flops calculation and memory requirement.

MLModelScope is currently under development and docs are here [MLModelScope Docs](https://rai-project.github.io/carml)