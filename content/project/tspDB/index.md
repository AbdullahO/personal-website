---
title: Time Series Prediction Database (tspDB)
summary: Enabling predictive query functionalities in PostgreSQL by building an additional “prediction index” for time-series data.
tags:
- Time Series Analysis
date: "2019-01-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""



url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---
<p>
<div style="text-align: justify"> 
A major bottleneck of the current Machine Learning (ML) workflow is the time consuming, error prone engineering required to get data from a datastore or a database (DB) to the point an ML algorithm can be applied to it. This is further exacerbated since ML algorithms are now trained on large volumes of data, yet we need predictions in real-time, especially in a variety of time-series applications such as finance and real-time control systems. 
</div>
</p>

<p>
<div style="text-align: justify"> 
Hence, In this project, we explore the feasibility of directly integrating prediction functionality on top of a data store or DB. Such a system ideally: (i) provides an intuitive prediction query interface which alleviates the unwieldy data engineering; (ii) provides state-of-the-art statistical accuracy while ensuring incremental model update, low model training time and low latency for making predictions. As the main deliverable, we explicitly instantiate a proof-of-concept, tspDB which directly integrates with PostgreSQL. You can access the open source implementation [here](https://tspdb.mit.edu).
</div>
</p>

<p>
<div style="text-align: justify"> 
In a recent paper, we rigorously test TSPS's statistical and computational performance against the state-of-the-art time series algorithms, including a Long-Short-Term-Memory (LSTM) neural network and DeepAR (industry standard deep learning library by Amazon). Statistically, on standard time series benchmarks, TSPS outperforms LSTM and DeepAR with 1.1-1.3x higher relative accuracy. Computationally, TSPS is 59-62x and 94-95x faster compared to LSTM and DeepAR in terms of median ML model training time and prediction query latency, respectively. Further, compared to PostgreSQL's bulk insert time and its SELECT query latency, TSPS is slower only by 1.3x and 2.6x respectively. That is, TSPS is a real-time prediction system in that its model training / prediction query time is similar to just inserting / reading data from a DB. As an algorithmic contribution, we introduce an incremental multivariate matrix factorization based time series method, which TSPS is built off.
</div>
</p>


## Resources:
- tspDB: Time Series Prediction Database [paper](/publication/tspDB).
- tspDB: Time Series Prediction Database [open source implementaion](https://tspdb.mit.edu).
