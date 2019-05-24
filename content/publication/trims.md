+++
title = "TrIMS: Transparent and Isolated Model Sharing for Low Latency Deep Learning Inference in Function as a Service Environments"
date = "2019-04-23"  # Schedule page publish date.
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adbul Dakkak", "Cheng Li", "Simon Garcia de Gonzalo", "Jinjun Xiong", "Wen-Mei Hwu"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "To appear in *IEEE CLOUD 2019 *"
publication_short = "To appear in *IEEE CLOUD*"

# Abstract and optional shortened version.
abstract = """Deep neural networks (DNNs) have become core computation components within low latency Function as a Service (FaaS) prediction pipelines. Cloud computing, as the de-facto backbone of modern computing infrastructure, has to be able to handle user-defined FaaS pipelines containing diverse DNN inference workloads while maintaining isolation and latency guarantees with minimal resource waste. The current solution for guaranteeing isolation and latency within FaaS is inefficient. A major cause of the inefficiency is the need to move large amount of data within and across servers. We propose TrIMS as a novel solution to address this issue. TrIMS is a generic memory sharing technique that enables constant data to be shared across processes or containers while still maintaining isolation between users. TrIMS consists of a persistent model store across the GPU, CPU, local storage, and cloud storage hierarchy, an efficient resource management layer that provides isolation, and a succinct set of abstracts, application APIs, and container technologies for easy and transparent integration with FaaS, Deep Learning (DL) frameworks, and user code. We demonstrate our solution by interfacing TrIMS with the Apache MXNet framework and demonstrate up to 24x speedup in latency for image classification models, up to 210x speedup for large models, and up to 8x system throughput improvement."""
abstract_short = "TrIMS is a generic memory sharing technique that enables constant data to be shared across processes or containers while still maintaining isolation between users."


# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#   projects = [""]

# Links (optional)
url_pdf = "https://arxiv.org/abs/1811.09732"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
