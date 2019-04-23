+++
title = "SemCluster: Clustering of Imperative Programming Assignments Based on Quantitative Semantic Features"
date = 2019-04-22T15:39:14-04:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Perry", "Dohyeong Kim", "Roopsha Samanta", "Xiangyu Zhang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "SemCluster: Clustering of Imperative Programming Assignments Based on Quantitative Semantic Features"
publication_short = ""

# Abstract.
abstract = """
A fundamental challenge in automated reasoning about pro-
gramming assignments at scale is clustering student submis-
sions based on their underlying algorithms. State-of-the-art
clustering techniques are sensitive to control structure vari-
ations, cannot cluster buggy solutions with similar correct
solutions, and either require expensive pair-wise program
analyses or training efforts. We propose a novel technique
that can cluster small imperative programs based on their
algorithmic essence: (A) how the input space is partitioned
into equivalence classes and (B) how the problem is uniquely
addressed within individual equivalence classes. We cap-
ture these algorithmic aspects as two quantitative semantic
program features that are merged into a program’s vector
representation. Programs are then clustered using their vec-
tor representations. The computation of our first semantic
feature leverages model counting to identify the number of
inputs belonging to an input equivalence class. The com-
putation of our second semantic feature abstracts the pro-
gram’s data flow by tracking the number of occurrences
of a unique pair of consecutive values of a variable dur-
ing its lifetime. The comprehensive evaluation of our tool
SemCluster on benchmarks drawn from solutions to small
programming assignments shows that SemCluster (1) gen-
erates far fewer clusters than other clustering techniques,
(2) precisely identifies distinct solution strategies, and (3)
boosts the performance of clustering-based program repair,
all within a reasonable amount of time.
""" 

# Summary. An optional shortened abstract.
summary = ""

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "pldi19_pres.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
