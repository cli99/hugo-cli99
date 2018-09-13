+++
# Date this page was created.
date = "2017-08-30"

# Project title.
title = "TOPS: Accelerating Collectives Using Tensor Core Units"

# Project summary to display on homepage.
summary = "Leverage NVIDIA’s Tensor Cores to express reduction and scan with matrix multiplication and show the benefits in terms of program simplicity, efficiency, and performance."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

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

Driven by deep learning, there has been a surge of specialized processors for matrix multiplication, referred to as Tensor Core Units (TCUs). These TCUs are capable of performing matrix multiplications on small matrices (usually 4 × 4 or 16 × 16) to accelerate the convolutional and recurrent neural networks in deep learning workloads. In this paper we lever- age NVIDIA’s TCU to express both reduction and scan with matrix multiplication and show the benefits — in terms of pro- gram simplicity, efficiency, and performance. Our algorithm exercises the NVIDIA TCUs which would otherwise be idle, achieves 89% − 98% of peak memory copy bandwidth, and is orders of magnitude faster (up to 100× for reduction and 3× for scan) than state-of-the-art methods for small segment sizes — common in machine learning and scientific applica- tions. Our algorithm achieves this while decreasing the power consumption by up to 22% for reduction and 16% for scan.
