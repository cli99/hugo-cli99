+++
title = "KLAP: Kernel launch aggregation and promotion for optimizing dynamic parallelism"
date = "2016-12-15"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Izzat El Hajj", "Juan Gomez-Luna", "Cheng Li", "Li-Wen Chang", "Dejan Milojicic", "Wen-mei Hwu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *International Symposium on Microarchitecture*, IEEE/ACM"
publication_short = "In *MICRO*"

# Abstract and optional shortened version.
abstract = "Dynamic parallelism on GPUs simplifies the programming of many classes of applications that generate paral-lelizable work not known prior to execution. However, modern GPUs architectures do not support dynamic parallelism efficiently due to the high kernel launch overhead, limited number of simultaneous kernels, and limited depth of dynamic calls a device can support. In this paper, we propose Kernel Launch Aggregation and Promotion (KLAP), a set of compiler techniques that improve the performance of kernels which use dynamic parallelism. Kernel launch aggregation fuses kernels launched by threads in the same warp, block, or kernel into a single aggregated kernel, thereby reducing the total number of kernels spawned and increasing the amount of work per kernel to improve occupancy. Kernel launch promotion enables early launch of child kernels to extract more parallelism between parents and children, and to aggregate kernel launches across generations mitigating the problem of limited depth. We implement our techniques in a real compiler and show that kernel launch aggregation obtains a geometric mean speedup of 6.58x over regular dynamic parallelism. We also show that kernel launch promotion enables cases that were not originally possible, improving throughput by a geometric mean of 30.44 x."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/klap-micro2016.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

# More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
