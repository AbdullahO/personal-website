---
title: Multivariate Time Series Analysis  
summary: Theoritical and empirical analysis of Multivariate Singular Spectrum Analysis (mSSA).
tags:
- Time Series Analysis
date: "2019-10-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

<p>
<div style="text-align: justify"> In this project, we analyze a variant of multivariate singular spectrum analysis (mSSA), a widely used multivariate time series method, which we find to perform competitively with respect to the state-of-art neural network time series methods (LSTM, DeepAR). Its restriction for single time series, singular spectrum analysis (SSA), has been analyzed recently. Despite its popularity, theoretical understanding of mSSA is absent. Towards this, we introduce a natural spatio-temporal factor model to analyze mSSA. 
</div>
</p>

<p>
<div style="text-align: justify">
In this project, we make three technical contributions. First, we establish that the "stacked" Page Matrix time series representation, the core data structure in mSSA (see figure above), has an approximate low-rank structure for a large class of time series models used in practice under the spatio-temporal factor model. Second, we extend the theory of online convex optimization to address the variant when the constraints are time-varying. Third, we extend the analysis prediction error analysis of Principle Component Regression beyond recent work to when the covariate matrix is approximately low-rank.
 </div>
</p>

![mSSA vs SOTA](elec_f_sigma.png)

## Resources:
- On Multivariate singular spectrum analysis [paper](/publication/mssa).
- Python implementation of our varaint of mSSA [repository](https://github.com/AbdullahO/mSSA).
