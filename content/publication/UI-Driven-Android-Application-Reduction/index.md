+++
title = "UI Driven Android Application Reduction"
date = 2017-11-07T14:30:49-05:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jianjun Huang", "Yousra Aafer", "David Perry", "Xiangyu Zhang", "Chen Tian"]

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
publication = "UI Driven Android Application Reduction"
publication_short = ""

# Abstract and optional shortened version.
abstract = "While smartphones and mobile apps have been an integral part of our life, modern mobile apps tend to contain a lot of rarely used functionalities. For example, applications contain advertisements and offer extra features such as recommended news stories in weather apps. While these functionalities are not essential to an app, they nonetheless consume power, CPU cycles and bandwidth. In this paper, we design a UI driven approach that allows customizing an Android app by removing its unwanted functionalities. In particular, our technique displays the UI and allows the user to select elements denoting functionalities that she wants to remove. Using this information, our technique automatically removes all the code elements related to the selected functionalities, including all the relevant background tasks. The underlying analysis is a type system, in which each code element is tagged with a type indicating if it should be removed. From the UI hints, our technique infers types for all other code elements and reduces the app accordingly. We implement a prototype and evaluate it on 10 real-world Android apps. The results show that our approach can accurately discover the removable code elements and lead to substantial resource savings in the reduced apps."
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
url_slides = ""
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
