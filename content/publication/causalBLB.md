+++
title = "A fast bootstrap algorithm for causal inference with large data"
date = "2023-02-06"

# Authors. Comma separated list, e.g. `["Michele Santacatterina"]`.
authors = ["M Kosko, L Wang, M Santacatterina"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "Work in progress"
publication_short = "Work in progress"

# Abstract and optional shortened version.
abstract = "Estimating causal effects from large experimental and observational data has become increasingly prevalent in both industry and research. The bootstrap is an intuitive and powerful technique used to construct standard errors and confidence intervals of estimators. Its application however can be prohibitively demanding in settings involving large data. In addition, modern causal inference estimators based on machine learning and optimization techniques exacerbate the computational burden of the bootstrap. The bag of little bootstraps has been proposed in non-causal settings for large data but has not yet been applied to evaluate the properties of estimators of causal effects. In this paper, we introduce a new bootstrap algorithm called causal bag of little bootstraps for causal inference with large data. The new algorithm significantly improves the computational efficiency of the traditional bootstrap while providing consistent estimates and desirable confidence interval coverage. We describe its properties, provide practical considerations, and evaluate the performance of the proposed algorithm in terms of bias, coverage of the true 95% confidence intervals, and computational time in a simulation study. We apply it in the evaluation of the effect of hormone therapy on the average time to coronary heart disease using a large observational data set from the Women's Health Initiative."



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
url_pdf = ""
url_preprint = ""
url_code = "https://github.com/mdk31/causalbootstrap"
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/1806.01083"}]
url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/2302.02859"}]

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

The **R** code is available here: https://github.com/mdk31/causalbootstrap


