+++
title = "Robust weights that optimally balance confounders for estimating the effect of binary and continuous treatments with time-to-event data"
date = "2020-10-15"

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
publication = "Submitted"
publication_short = "*Submitted*"

# Abstract and optional shortened version.
abstract = "Covariate balance is crucial in obtaining unbiased estimates of treatment effects in observational studies. Methods based on Inverse Probability Weights (IPW) have been widely used to estimate treatment effects with observational data. Machine learning techniques have been proposed to estimate propensity scores. These techniques however target accuracy instead of covariate balance. Methods that target covariate balance have been successfully proposed and largely applied to estimate treatment effects on continuous outcomes. However, in many medical and epidemiological applications, the interest lies in estimating treatment effects on time-to-an-event outcomes. In this paper, we start by presenting robust orthogonality weights (ROW), a set of weights obtained by solving a quadratic constrained optimization problem that maximizes precision while constraining covariate balance defined as the sample correlation between confounders and treatment. By doing so, ROW optimally deal with both binary and continuous treatments. We then evaluate the performance of the proposed weights in estimating hazard ratios of binary and continuous treatments with time-to-event outcomes in a simulation study. We finally apply ROW on the evaluation of the effect of hormone therapy on time to coronary heart disease and on the effect of red meat consumption on time to colon cancer among 24,069 postmenopausal women enrolled in the Women's Health Initiative observational study."



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
url_pdf = "https://arxiv.org/pdf/2010.07695.pdf"
url_preprint = "/files/ROW.pdf"
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
