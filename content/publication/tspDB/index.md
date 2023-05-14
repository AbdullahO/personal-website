
---
title: "tspDB: Time Series Predict DB"
authors:
- Anish Agarwal
- Abdullah Alomar
- Devavrat Shah

date: "2020-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2020 Competition and Demonstration Track"
#publication_short: "NeurIPS 2020 Demo"

abstract: A major bottleneck of the current Machine Learning (ML) workflow is the time consuming,error prone engineering required to get data from a datastore or a database (DB) to the point an ML algorithm can be applied to it. This is further exacerbated since ML algorithms are now trained on large volumes of data, yet we need predictions in real-time, especially in a variety of time-series applications such as finance and real-time control systems. Hence, we explore the feasibility of directly integrating prediction functionality on top of a data store or DB. Such a system ideally: (i) provides an intuitive prediction query interface which alleviates the unwieldy data engineering; (ii) provides state-of-the-art statistical accuracy while ensuring incremental model update, low model training time and low latency for making predictions. 
# As the main contribution we explicitly instantiate a proof-of-concept, tspDB which directly integrates with PostgreSQL. We rigorously test tspDB’s statistical and computational performance against the state-of-the-art time series algorithms, including a Long-Short-Term-Memory (LSTM) neural network and DeepAR (industry standard deep learning library by Amazon). Statistically, on standard time series benchmarks, tspDB outperforms LSTM and DeepAR with 1.1-1.3x higher relative accuracy. Computationally, tspDB is 59-62x and 94-95x faster compared to LSTM and DeepAR in terms of median ML model training time and prediction query latency, respectively. Further, compared to PostgreSQL’s bulk insert time and its SELECT query latency, tspDB is slower only by 1.3x and 2.6x respectively. That is, tspDB is a real-time prediction system in that its model training / prediction query time is similar to just inserting / reading data from a DB. As an algorithmic contribution, we introduce an incremental multivariate matrix factorization based time series method, which tspDB is built off. We show this method also allows one to produce reliable prediction intervals by accurately estimating the time-varying variance of a time series, thereby addressing an important problem in time series analysis.

# Summary. An optional shortened abstract.
summary: NeurIPS 2020 Demo
# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'http://proceedings.mlr.press/v133/agarwal21a/agarwal21a.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: 'https://tspdb.mit.edu'
# url_slides: 'https://drive.google.com/file/d/1wlbfLZBYi-hljjLsEcK0_9NzpWhSipUh/view?usp=sharing'
# url_source: ''
url_video: 'https://www.dropbox.com/s/9zc2lpej20bj9j2/tspDB.mp4?dl=0'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---


