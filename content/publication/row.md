+++
title = "Robust weights that optimally balance confounders for estimating marginal hazard ratios"
date = "2023-01-12"

# Authors. Comma separated list, e.g. `["Michele Santacatterina"]`.
authors = ["M Santacatterina"]

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
publication = "Statistical Methods in Medical Research"
publication_short = "*SMMR*"

# Abstract and optional shortened version.
abstract = "Covariate balance is crucial in obtaining unbiased estimates of treatment effects in observational studies. Methods that target covariate balance have been successfully proposed and largely applied to estimate treatment effects on continuous outcomes. However, in many medical and epidemiological applications, the interest lies in estimating treatment effects on time-to-event outcomes. With this type of data, one of the most common estimands of interest is the marginal hazard ratio of the Cox proportional hazards model. In this article, we start by presenting robust orthogonality weights, a set of weights obtained by solving a quadratic constrained optimization problem that maximizes precision while constraining covariate balance defined as the correlation between confounders and treatment. By doing so, robust orthogonality weights optimally deal with both binary and continuous treatments. We then evaluate the performance of the proposed weights in estimating marginal hazard ratios of binary and continuous treatments with time-to-event outcomes in a simulation study. We finally apply robust orthogonality weights in the evaluation of the effect of hormone therapy on time to coronary heart disease and on the effect of red meat consumption on time to colon cancer among 24,069 postmenopausal women enrolled in the Women’s Health Initiative observational study."



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
url_pdf = "https://journals.sagepub.com/doi/abs/10.1177/09622802221146310"
url_preprint = ""
url_code = "https://github.com/michelesantacatterina/ROW"
url_dataset = "https://github.com/michelesantacatterina/ROW-time-to-event"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/1806.01083"}]
url_custom = [{name = "arXiv", url = "https://arxiv.org/abs/2010.07695"}]

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

The **R** package (with instructions on how to install the package and several examples) is available here: https://github.com/michelesantacatterina/ROW

The code for the simulations and the case studies analyses is provided here: 
https://github.com/michelesantacatterina/ROW-time-to-event
