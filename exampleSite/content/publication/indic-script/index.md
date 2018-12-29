+++
title = "RNNs based Indic word-wise script identification using character-wise training"
date = 2017-07-16T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Rohun Tripathi", "Aman Gill", "Riccha Tripati"]

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
publication = "Accepted at ICPRS 2017 (Oral)"

# Abstract and optional shortened version.
abstract = "This paper presents a novel methodology of Indic handwritten script recognition using Recurrent Neural Networks and addresses the problem of script recognition in poor data scenarios, such as when only character level online data is available. It is based on the hypothesis that curves of online character data comprise sufficient information for prediction at the word level. Online character data is used to train RNNs using BLSTM architecture which are then used to make predictions of online word level data. These prediction results on the test set are at par with prediction results of models trained with online word data, while the training of the character level model is much less data intensive and takes much less time. Performance for binary-script models and then 5 Indic script models are reported, along with comparison with HMM models.The system is extended for offline data prediction. Raw offline data lacks the temporal information available in online data and required for prediction using models trained with online data. To overcome this, stroke recovery is implemented and the strokes are utilized for predicting using the online character level models. The performance on character and word level offline data is reported."

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["computer-vision", "deep-learning"]

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Arxiv", url = "https://arxiv.org/abs/1709.03209"}]

# Links (optional).
url_pdf='https://arxiv.org/pdf/1709.03209.pdf'
url_code='https://github.com/rohun-tripathi/Indic-Script-Recognition-RnnLib'

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""

# Could not attend due to funding issues.

+++