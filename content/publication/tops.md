+++
title = "Accelerating Reduction and Scan Using Tensor Core Units"
date = "2019-04-23"  # Schedule page publish date.
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Adbul Dakkak", "Cheng Li", "Jinjun Xiong", "Isaac Gelado", "Wen-Mei Hwu"]

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
publication = "To appear in *International Conference on Supercomputing 2019*"
publication_short = "To appear in *ICS*"

# Abstract and optional shortened version.
abstract = "Driven by deep learning, there has been a surge of specialized processors for matrix multiplication, referred to as Tensor Core Units (TCUs). These TCUs are capable of performing matrix multiplications on small matrices (usually 4 X 4 or 16 X 16) to accelerate HPC and deep learning workloads. Although TCUs are prevalent and promise increase in performance and/or energy efficiency and are heavily used within supercomputers to achieve exascale performance, they suffer from over specialization — with only general matrix multiplication (GEMM) operations on small matricies being supported. In this paper we express both reduction and scan in terms of matrix multiplication operations and map them onto TCUs. To our knowledge, this paper is the first to trying to broaden the class of algorithms expressible as TCU operations and is the first to show benefits of this mapping in terms of: program simplicity, efficiency, and performance. We implement the algorithms using NVIDIA V100 TCUs and achieve 89% − 98% of peak memory copy bandwidth, and are orders of magnitude faster (up to 100x for reduction and 3x for scan) than state-of-the-art methods for small segment sizes (common in HPC and deep learning applications). Our implementation achieves this while decreasing the power consumption by up to 22% for reduction and 16% for scan."
abstract_short = "In this paper we express reduction and scan in terms of matrix multiplication operations and map them onto Tensor Core Units."


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
url_pdf = "https://arxiv.org/abs/1811.09736"
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
