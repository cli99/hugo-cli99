+++
title = "Matrix Factorization on GPUs with Memory Optimization and Approximate Computing"
date = "2018-05-13"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wei Tan", "Shiyu Chang", "Liana Fong", "Cheng Li", "Zijun Wang", "LiangLiang Cao"]

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
publication = "In *International Conference on Parallel Processing*"
publication_short = "In *ICPP*"

# Abstract and optional shortened version.
abstract = "Matrix factorization (MF) discovers latent features from observations, which has shown great promises in the fields of collaborative filtering, data compression, feature extraction, word embedding, etc. While many problem-specific optimization techniques have been proposed, alternating least square (ALS) remains popular due to its general applicability (e.g. easy to handle positive-unlabeled inputs), fast convergence and parallelization capability. Current MF implementations are either optimized for a single machine or with a need of a large computer cluster but still are insufficent. This is because a single machine provides limited compute power for large-scale data while multiple machines suffer from the network communication bottleneck. To address the aforementioned challenge, accelerating ALS on garphics processing units (GPUs) is a promising direction. We propose a novel approach in this paper. We analyze the procedure of MF and focus on enhancing the efficiency via both memory optimization and approximate computing. The former exploits GPU memory hierarchy to increase data reuse, while the later reduces unnecessary computing without hurting the convergence of the learning algorithm. Extensive experiments on large-scale datasets show that our system not only outperforms all competing CPU solutions by a large margin but also has a 2x-4x performance gain compared to the state-of-the-art GPU solution. Our implemen- tations are open-sourced and publicly available."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "pdf/mfgpu-icpp2018.pdf"
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
