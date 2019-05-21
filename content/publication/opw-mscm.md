+++
title = "Optimal probability weights for estimating causal effects of time-varying treatments with marginal structural Cox models"
date = "2018-08-27"

# Authors. Comma separated list, e.g. `["Michele Santacatterina", "Celia Garcia Pareja", "Rino Bellocco", "Anna Mia Ekström", "Anders Sonnerbörg", "Matteo Bottai"]`.
authors = ["M Santacatterina", "C Pareja Garcia", "R Bellocco", "AM Ekström", "A Sonnerbörg", "M Bottai"]

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
publication = "In *Statistics in Medicine*"
publication_short = "In *Statistics in Medicine*"

# Abstract and optional shortened version.
abstract = "Marginal structural Cox models have been used to estimate the causal effect of a time-varying treatment on a survival outcome in the presence of time-dependent confounders. These methods rely on the positivity assumption, which states that the propensity scores are bounded away from zero and one. Practical violations of this assumption are common in longitudinal studies, resulting in extreme weights that may yield erroneous inferences. Truncation, which consists of replacing outlying weights with less extreme ones, is the most common approach to control for extreme weights to-date. While truncation reduces the variability in the weights and the consequent sampling variability of the estimator, it can also introduce bias. Instead of truncated weights, we propose using optimal probability weights, defined as those that have a specified variance and the smallest Euclidean distance from the original, untruncated weights. The set of optimal weights is obtained by solving a constrained quadratic optimization problem. The proposed weights are evaluated in a simulation study and applied to the assessment of the effect of treatment on time to death among people in Sweden who live with human immunodeficiency virus and inject drugs."

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
url_pdf = "https://nbviewer.jupyter.org/github/michelesantacatterina/docs/blob/master/Optimal%20probability%20weights%20for%20MSCM%20rev.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""



# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "Statistics in Medicine", url = "https://onlinelibrary.wiley.com/doi/abs/10.1002/sim.8080"}]

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