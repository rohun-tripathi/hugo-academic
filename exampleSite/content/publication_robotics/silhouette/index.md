+++
title = "Path Planning in Ellipsoidal Configuration Space using Silhouette method"
date = 2016-07-02T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Rohun Tripathi", "Bhaskar Dasgupta"]

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
# publication = "Undergraduate Thesis"

# Abstract and optional shortened version.
abstract = "This work presents the methodology used for implementing Silhouette method for Robot motion planning in Configuration spaces in arbitrary dimensions. A collection of ellipsoids are used to design and implement this Configuration Space of the robot. The path is then designed based on the Silhouette method as described by Canny [2], which creates semi-free paths in the configuration space and is complete. Djikstra’s algorithm is used to connect the paths obtained. This report introduces each of the key areas of the project and follows a step by step implementation of each. To conclude, we discuss the model output by our implementation and future directions of this project."

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
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['robotics', 'applied-math']

# Links (optional).
url_pdf = "files/paperSilhouette.pdf"
url_code = "https://github.com/rohun-tripathi/Robot-Motion-Planning-Silhouette"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

Abstract. This work presents the methodology used for implementing Silhouette method for Robot motion planning in Configuration spaces in arbitrary dimensions. A collection of ellipsoids are used to design and implement this Configuration Space of the robot. The path is then designed based on the Silhouette method as described by Canny [2], which creates semi-free paths in the configuration space and is complete. Djikstra’s algorithm is used to connect the paths obtained. This report introduces each of the key areas of the project and follows a step by step implementation of each. To conclude, we discuss the model output by our implementation and future directions of this project.