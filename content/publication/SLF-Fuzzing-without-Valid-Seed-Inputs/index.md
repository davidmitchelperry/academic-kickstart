+++
title = "SLF: Fuzzing Without Valid Seed Inputs"
date = 2019-04-22T15:31:41-04:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wei You", "Xuwei Liu", "Shiqing Ma", "David Perry", "Xiangyu Zhang", "Bin Lang"]

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
publication = "SLF: Fuzzing without Valid Seed Inputs"
publication_short = ""

# Abstract.
abstract = """
Fuzzing is an important technique to detect software
bugs   and   vulnerabilities.   It   works   by   mutating   a   small   set
of   seed   inputs   to   generate   a   large   number   of   new   inputs.
Fuzzers’  performance  often  substantially  degrades  when  valid
seed inputs are not available. Although existing techniques such
as  symbolic  execution  can  generate  seed  inputs  from  scratch,
they  have  various  limitations  hindering  their  applications  in
real-world  complex  software.  In  this  paper,  we  propose  a  novel
fuzzing technique that features the capability of generating valid
seed  inputs.  It  piggy-backs  on  AFL  to  identify  input  validity
checks  and  the  input  fields  that  have  impact  on  such  checks.
It  further  classifies  these  checks  according  to  their  relations  to
the input. Such classes include arithmetic relation, object offset,
data  structure  length  and  so  on.  A  multi-goal  search  algorithm
is developed to apply class-specific mutations in order to satisfy
inter-dependent  checks  all  together.  We  evaluate  our  technique
on 20 popular benchmark programs collected from other fuzzing
projects  and  the  Google  fuzzer  test  suite,  and  compare  it  with
existing  fuzzers  AFL  and  AFLFast,  symbolic  execution  engines
KLEE and S2E, and a hybrid tool Driller that combines fuzzing
with symbolic execution. The results show that our technique is
highly  effective  and  efficient,  out-performing  the  other  tools. 
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
url_slides = ""
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
