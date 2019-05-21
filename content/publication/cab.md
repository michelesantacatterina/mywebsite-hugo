+++
title = "CAB: Continuous Adaptive Blending Estimator for Policy Evaluation and Learning"
date = "2019-05-01"



# Authors. Comma separated list, e.g. `["Yi Su", "Lequn Wang", "Michele Santacatterina", "Thorsten Joachims"]`.
authors = ["Y Su", "L Wang", "M Santacatterina", "T Joachims"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Accepted at NIPS 2018 Workshop on Causal Learning and ICML 2019"
publication_short = "*Accepted at NeurIPS 2018 Workshop on Causal Learning and ICML 2019*"

# Abstract and optional shortened version.
abstract = "The ability to perform offline A/B-testing and off-policy learning using logged contextual bandit feedback is highly desirable in a broad range of applications, including recommender systems, search engines, ad placement, and personalized health care. Both offline A/B-testing and offpolicy learning require a counterfactual estimator that evaluates how some new policy would have performed, if it had been used instead of the logging policy. In this paper, we present and analyze a family of counterfactual estimators which subsumes most estimators proposed to date. Most importantly, this analysis identifies a new estimator – called Continuous Adaptive Blending (CAB) – which enjoys many advantageous theoretical and practical properties. In particular, it can be substantially less biased than clipped Inverse Propensity Score (IPS) weighting and the Direct Method, and it can have less variance than Doubly Robust and IPS estimators. In addition, it is subdifferentiable such that it can be used for learning, unlike the SWITCH estimator. Experimental results show that CAB provides excellent evaluation accuracy and outperforms other counterfactual estimators in terms of learning performance."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = [""]

# Links (optional).
#url_project = ""
url_pdf = "https://arxiv.org/pdf/1811.02672.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/1811.02672"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++


