+++
# Date this page was created.
date = "2017-08-30"

# Project title.
title = "MLModelScope (CarML)"

# Project summary to display on homepage.
summary = "An open-source framework agnostic platform for performing evaluations and profiling on ML/DL models across datasets, frameworks, and systems to analyze accuracy, efficiency, and performance."

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

The current landscape of Machine Learning (ML) and Deep Learning (DL) is rife with non-uniform models, frameworks, and system stacks but lacks standard tools to evaluate and profile models or systems. Due to the absence of such tools, the current practice for evaluating and comparing the benefits of proposed AI innovations (be it hardware or software) on end-to-end AI pipelines is both arduous and error prone — stifling the adoption of the innovations.

MLModelScope is a hardware/software agnostic, extensible and customizable platform for evaluating and profiling ML models across datasets/frameworks/hardware, and within AI application pipelines. MLModelScope lowers the cost and effort for performing model evaluation and profiling, making it easier for others to reproduce, evaluate, and analyze accuracy or performance claims of models and systems.

It is designed to aid in:

- reproducing and comparing with published models, and designing models with performance and deployment in mind,
- understanding the model performance (within realworld AI workflows) and its interaction with all levels of the hardware/software stack
- discovering models, frameworks and hardware that are applicable to users’ datasets.

To achieve this, MLModelScope:

- provides a consistent evaluation, aggregation, and reporting system by defining
  techniques to specify and provision workflows with HW/SW stacks
  abstractions for evaluation and profiling using different frameworks
  data consumption for evaluation outputs
- enables profiling of experiments throughout the entire pipeline and at different abstraction levels (application, model, framework, layer, library and hardware, as shown on the right)
- is framework and hardware agnostic - with current support for TensorFlow, MXNet, TensorRT, Caffe, Caffe2, CNTK running on X86, PowerPC, and ARM CPU with GPU and FPGA
- is extensible and customizable - allowing users to extend MLModelScope by adding models, frameworks, or library and system profilers, and use
- can run experiments on separate machines, and behind firewall (does not exposing model weights or machine specification)
- allows parallel evaluation (multiple instantiations of the same experiment set-up across systems)
- specifies model and framework resources as asset files which can be added easily, even at runtime

MLModelScope can be used as an application with a command line, API or web interface, or can be compiled into a standalone library. We also provide an online hub of continuously updated assets, evaluation results, and access to hardware resources — allowing users to discover and evaluate models without installing or configuring systems.

Learn more at [MLModelScope](https://mlmodelscope.org/) and [Docs](https://docs.mlmodelscope.org/)
