+++
# Date this page was created.
date = "2017-08-30"

# Project title.
title = "KLAP"

# Project summary to display on homepage.
summary = "Kernel Lauch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of GPU kernels which use dynamic parallelism."

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

Dynamic parallelism on GPUs simplifies the programming of many classes of applications that generate paral-lelizable work not known prior to execution. However, modern GPUs architectures do not support dynamic parallelism efficiently due to the high kernel launch overhead, limited number of simultaneous kernels, and limited depth of dynamic calls a device can support.

We proposed Kernel Lauch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of kernels which use dynamic parallelism. More details in the [paper](/publication/klap/).
