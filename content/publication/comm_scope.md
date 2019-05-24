+++
title = "Evaluating Characteristics of CUDA Communication Primitives on High-Bandwidth Interconnects"
date = 2019-04-09T00:00:00  # Schedule page publish date.
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Carl Pearson", "Adbul Dakkak", "Sarah Hashash", "Cheng Li", "I-Hsin Chung", "Jinjun Xiong", "Wen-Mei Hwu"]

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
publication = "In *2019 ACM/SPEC International Conference on Performance Engineering*"
publication_short = "In *ICPE*"

# Abstract and optional shortened version.
abstract = """Data-intensive applications such as machine learning and analytics have created a demand for faster interconnects to avert the memory bandwidth wall and allow GPUs to be effectively leveraged for lower compute intensity tasks. This has resulted in wide adoption of heterogeneous systems with varying underlying interconnects, and has delegated the task of understanding and copying data to the system or application developer. No longer is a malloc followed by memcpy the only or dominating modality of data transfer; application developers are faced with additional options such as unified memory and zero-copy memory. Data transfer performance on these systems is now impacted by many factors including data transfer modality, system interconnect hardware details, CPU caching state, CPU power management state, driver policies, virtual memory paging efficiency, and data placement.

This paper presents Comm|Scope, a set of microbenchmarks designed for system and application developers to understand memory transfer behavior across different data placement and exchange scenarios.
Comm|Scope comprehensively measures the latency and bandwidth of CUDA data transfer primitives, and avoids common pitfalls in ad-hoc measurements by controlling CPU caches, clock frequencies, and avoids measuring synchronization costs imposed by the measurement methodology where possible.
This paper also presents an evaluation of Comm|Scope on systems featuring the POWER and x86 CPU architectures and PCIe 3, NVLink 1, and NVLink 2 interconnects.
These systems are chosen as representative configurations of current high-performance GPU platforms.
Comm|Scope measurements can serve to update insights about the relative performance of data transfer methods on current systems.
This work also reports insights for how high-level system design choices affect the performance of these data transfers, and how developers can optimize applications on these systems."""
abstract_short = "This paper presents Comm|Scope, a set of microbenchmarks designed for system and application developers to understand memory transfer behavior across different data placement and exchange scenarios."


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
url_pdf = "pdf/comm-scope-icpe19.pdf"
url_preprint = ""
url_code = "https://github.com/c3sr/comm_scope"
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


* Best Paper for the ICPE research track papers
* Functional ACM Artifact Evaluation.
