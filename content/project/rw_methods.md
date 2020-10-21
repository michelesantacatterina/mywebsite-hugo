+++
# Date this page was created.
date = "2020-01-01"

# Project title.
title = "Novel statistical methods for the optimal use of real-world patient data to improve clinical decision-making"

# Project summary to display on homepage.
summary = "The goal of this project is to developed novel biostatistical methods that optimally leverage trials’ results and data from electronic medical registries which is more representative of real-world clinical practice."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = []

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = true

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++


Evidence-based medicine requires investigators to include the best available evidence into their clinical decision-making process. The best evidence regarding the causal effect of a treatment can be provided by properly conducted randomized trials. However, randomized trials, can be costly, infeasible, or unethical. 

The goal of this project is to developed novel biostatistical methods that optimally leverage trials’ results and data from electronic medical registries which is more representative of real-world clinical practice.


## Optimally estimating treatment effects from observational data

### Controlling extreme weights

Because traditional biostatistical methodologies to estimate the causal effect of a treatment using data from electronic medical registries, such as inverse probability weighting, may lead to erroneous results due to practical positivity violation (lack of overlap), I developed a novel biostatistical technique based on a constrained nonlinear optimization problem that provide optimal weights for inference with constrained precision. I found that the method proposed outperformed traditional biostatistical methodologies, such as truncated inverse probability weights, with respect to bias and mean squared error, and I applied it to evaluate the impact of CD4 cell count at treatment initiation among HIV infected patients. 

- Santacatterina, M., Bottai, M., [*Optimal probability weights for inference with constrained precision*](http://nbviewer.jupyter.org/github/michelesantacatterina/docs/blob/master/Optimal%20probability%20weights%20for%20inference%20with%20constrained%20precision.pdf), JASA, 2018

- Santacatterina, M., et.al., [*Optimal probability weights for estimating causal effects of time-varying treatments with marginal structural Cox models*](https://nbviewer.jupyter.org/github/michelesantacatterina/docs/blob/master/Optimal%20probability%20weights%20for%20MSCM%20rev.pdf), Statistics in Medicine, 2018

### Mitigating model misspecification while controlling extreme weights

To mitigate possible model misspecification while simultaneously controlling for precision, I worked on a method that find weights that directly maximize covariate balance. I found that the proposed methodology outperformed state-of-the-art techniques, and I applied it to evaluate the effect of a spine surgical intervention on patient-reported outcomes. 

- Kallus, N., Pennicooke, B., Santacatterina, M., [*More robust estimation of sample average treatment effects using Kernel Optimal Matching in an observational study of spine surgical interventions*](https://docs.google.com/viewer?url=https://github.com/michelesantacatterina/docs/raw/master/More%20robust%20estimation%20of%20SATE%20using%20KOM.pdf), Under review on Statistics in Medicine, 2019

- Kallus, N., Santacatterina, M., [*Optimal Estimation of Generalized Average Treatment Effects via Kernel Optimal Matching*](https://arxiv.org/pdf/1908.04748.pdf), 2019

I extendend the proposed methodology to control for time-dependent confounders, which are confounders that are affected by previous treatments and impacts future ones.

- Kallus, N., Santacatterina, M., [*Optimal balancing of time-dependent confounders for marginal structural models*](https://docs.google.com/viewer?url=https://github.com/michelesantacatterina/docs/raw/master/Optimal%20balancing%20of%20time-dependent%20confounders%20for%20MSM.pdf), 2019

I extended the proposed methodology to optimally to balance confounders to estimate causal effects of continuous treatments.

- Kallus, N., Santacatterina, M., [*Kernel Optimal Orthogonality Weighting: A Balancing Approach to Estimating Effects of Continuous Treatment*](https://arxiv.org/pdf/1910.11972), Work in progress, 2019

I proposed a new robust weights that balance confounders for both binary and continuous treatments with time-to-event-data. I applied the proposed weights on the evaluation of the effect of hormone therapy on time to coronary heart disease and on the effect of red meat consumption on time to colon cancer among 24,069 postmenopausal women enrolled in the Women’s Health Initiative observational study.

Santacatterina, M., [*Robust weights that optimally balance confounders for estimating the effect of binary and continuous treatments with time-to-event data*](https://docs.google.com/viewer?url=https://arxiv.org/pdf/2010.07695.pdf), 2020


## Generalizing trials' results

Because trial participants may not be representative of the real-world population, I developed a biostatistical methodology that provide robust weights to generalize trials’ results to target populations. I found that the method outperformed traditional state-of-the-art methods and I applied it to generalize the effect of peer support on viral failure among HIV infected patients from Vietnam to the United States.

- Kallus, N., Santacatterina, M., [*Optimal Estimation of Generalized Average Treatment Effects via Kernel Optimal Matching*](https://arxiv.org/pdf/1908.04748.pdf), 2019

## Precision medicine

To evaluate and learn optimal individualized treatment regimes, I proposed the used of a doubly robust estimator and present a method that optimally combines weighted and outcome modeling techniques. I found that the proposed methodology performs well in terms of mean square error and bias.

- Su, Y., Wang, L., Santacatterina, M., Thorsten, J., [*CAB: Continuous Adaptive Blending Estimator for Policy Evaluation and Learning*](https://arxiv.org/pdf/1811.02672.pdf), Accepted at NeurIPS 2018 Workshop on Causal Learning and ICML 2019, 2019


