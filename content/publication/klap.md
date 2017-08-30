+++
date = "2016-12-15"
title = "KLAP: Kernel launch aggregation and promotion for optimizing dynamic parallelism"
authors = ["Izzat El Hajj", "Juan Gomez-Luna", "Cheng Li", "Li-Wen Chang", "Dejan Milojicic", "Wen-mei Hwu"]

abstract = "Dynamic parallelism on GPUs simplifies the programming of many classes of applications that generate paral-lelizable work not known prior to execution. However, modern GPUs architectures do not support dynamic parallelism efficiently due to the high kernel launch overhead, limited number of simultaneous kernels, and limited depth of dynamic calls a device can support. In this paper, we propose Kernel Launch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of kernels which use dynamic parallelism. Kernel launch aggregation fuses kernels launched by threads in the same warp, block, or kernel into a single aggregated kernel, thereby reducing the total number of kernels spawned and increasing the amount of work per kernel to improve occupancy. Kernel launch promotion enables early launch of child kernels to extract more parallelism between parents and children, and to aggregate kernel launches across generations mitigating the problem of limited depth. We implement our techniques in a real compiler and show that kernel launch aggregation obtains a geometric mean speedup of 6.58x over regular dynamic parallelism. We also show that kernel launch promotion enables cases that were not originally possible, improving throughput by a geometric mean of 30.44 x."

image = ""
image_preview = ""
math = false
publication = "MICRO 2016 - *the 49th Annual IEEE/ACM International Symposium on Microarchitecture*"

url_code = ""
url_dataset = ""
url_pdf = "pdf/klap-micro2016.pdf"
url_project = ""
url_slides = ""
url_video = ""

selected = false
+++