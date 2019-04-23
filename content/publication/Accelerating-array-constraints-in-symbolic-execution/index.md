+++
title = "Accelerating Array Constraints in Symbolic Execution"
date = 2017-07-07T14:27:34-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Perry", "Andrea Mattavelli", "Xiangyu Zhang", "Cristian Cadar"]

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
publication = "Accelerating array constraints in symbolic execution"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Despite significant recent advances, the effectiveness of symbolic execution is limited when used to test complex, real-world software.  One of the main scalability challenges is related to constraint solving: large applications and long exploration paths lead to complex constraints, often involving big arrays indexed by symbolic expressions.  In this paper, we propose a set of semantics-preserving transformations for array operations that take advantage of contextual information collected during symbolic execution. Our transformations lead to simpler encodings and hence better performance in constraint solving. The results we obtain are encouraging: we show, through an extensive experimental analysis, that our transformations help to significantly improve the performance of symbolic execution in the presence of arrays. We also show that our transformations enable the analysis of new code, which would be otherwise out of reach for symbolic execution."
abstract_short = ""

# Is this a selected publication? (true/false)
selected = false

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

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = "issta17_pres.pdf"
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
