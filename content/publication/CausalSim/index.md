
---
title: "CausalSim: A Causal Framework for Unbiased Trace-Driven Simulation"
authors:
- Abdullah Alomar
- Pouya Hamadanian
- Arash Nasr-Esfahany
- Anish Agarwal
- Mohammad Alizadeh
- Devavrat Shah

date: "2023-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-01T00:00:00Z"
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NSDI 23"
#publication_short: "ArXiv"

# abstract: We present CausalSim, a causal framework for unbiased trace-driven simulation. Current trace-driven simulators assume that the interventions being simulated (eg, a new algorithm) would not affect the validity of the traces. However, real-world traces are often biased by the choices algorithms make during trace collection, and hence replaying traces under an intervention may lead to incorrect results. CausalSim addresses this challenge by learning a causal model of the system dynamics and latent factors capturing the underlying system conditions during trace collection. It learns these models using an initial randomized control trial (RCT) under a fixed set of algorithms, and then applies them to remove biases from trace data when simulating new algorithms.

# Summary. An optional shortened abstract.
summary: NSDI 2023 
# tags:
# - Source Themes
# featured: true

# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.usenix.org/system/files/nsdi23-alomar.pdf'
# url_code: ''
# url_dataset: ''
# url_poster: ''
url_project: 'https://causalsim.csail.mit.edu'
url_slides: 'https://causalsim.csail.mit.edu/content/CausalSim_NSDI.pptx'
# url_source: ''
# url_video: ''

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


