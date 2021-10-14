
---
title: "Change Point Detection via Multivariate Singular Spectrum Analysis"
authors:
- Arwa Alanqary
- Abdullah Alomar
- Devavrat Shah

date: "2021-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2021"
#publication_short: "ArXiv"

# abstract: The objective of change point detection (CPD) is to detect significant and abrupt changes in the dynamics of the underlying system of interest through multivariate time series observations. In this work, we develop and analyze an algorithm for CPD that is inspired by a variant of the classical singular spectrum analysis (SSA) approach for time series by combining it with the classical cumulative sum (CUSUM) statistic from sequential hypothesis testing. In particular, we model the underlying dynamics of multivariate time series observations through the spatio-temporal model introduced recently in the multivariate SSA (mSSA) literature. The change point in such a setting corresponds to a change in the underlying spatio-temporal model. As the primary contributions of this work, we develop an algorithm based on CUSUM-statistic to detect such change points in an online fashion. We extend the analysis of CUSUM statistics, traditionally done for the setting of independent observations, to the dependent setting of (multivariate) time series under the spatio-temporal model. Specifically, for a given parameter h >0, our method achieves the following desirable trade-off: when a change happens, it detects it within $$O(h)$$ time delay on average, while in the absence of change, it does not declare false detection for at least $$\exp(\Omega(h))$$ time length on average. We conduct empirical experiments using benchmark and synthetic datasets. We find that the proposed method performs competitively or outperforms the state-of-the-art change point detection methods across datasets.

# Summary. An optional shortened abstract.
summary: NeurIPS 2021
# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2102.06961'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['mSSA']


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---


