+++
# Date this page was created.
date = "2017-08-30"

# Project title.
title = "TrIMS"

# Project summary to display on homepage.
summary = "Transparent and Isolated Model Sharing for Low Latency Deep Learning Inference in Function as a Service Environments"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["past"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ":smile:"

+++

Deep neural networks (DNNs) have become core computation components within low latency Function as a Service (FaaS) prediction pipelines: including image recognition, object detection, natural language processing, speech synthesis, and personalized recommendation pipelines. Cloud computing, as the de-facto backbone of modern computing infrastructure for both enterprise and consumer applications, has to be able to handle user-defined pipelines of diverse DNN inference workloads while maintaining isolation and latency guarantees, and minimizing resource waste. The current solution for guaranteeing isolation within FaaS is suboptimal
— suffering from "cold start" latency. A major cause of such inefficiency is the need to move large amount of model data within and across servers. We propose TrIMS as a novel solution to address these issues. Our proposed solution consists of a persistent model store across the GPU, CPU, local storage, and cloud storage hierarchy, an efficient resource management layer that provides isolation, and a succinct set of application APIs and container technologies for easy and transparent integration with FaaS, Deep Learning (DL) frameworks, and user code. We demonstrate our solution by interfacing TrIMS with the Apache MXNet framework and demonstrate up to 24× speedup in latency for image classification models and up to 210× speedup for large models. We achieve up to 8× system throughput improvement.
