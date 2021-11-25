---
title: Deep Video Reconstruction From fMRI Signals
summary: fMRI is noisy high-dimensional data with poor temporal resolution. I am using fMRI data to predict the activations of stimulus video and use propose a Deep Video Prior to reconstruct the video by feature inversion while constraining it in the manifold of natural videos.

tags:
- Machine Learning
- Computer Vision
date: "2021-11-25"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
date_end: ""
show_date: true

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

**Status**: Ongoing (Since Dec 2020)

I am being advised by [Prof. Radoslaw Martin Cichy](http://userpage.fu-berlin.de/rmcichy/) ([Neural Dynamics of Visual Cognition Lab](https://www.ewi-psy.fu-berlin.de/en/einrichtungen/arbeitsbereiche/neural_dyn_of_vis_cog/index.html), Freie Universität Berlin) and [Prof. Gemma Roig](http://www.cvai.cs.uni-frankfurt.de/team.html) ([Computer Vision and Artificial Intelligence Lab](http://www.cvai.cs.uni-frankfurt.de/), Goethe University) for my master's thesis. We are decoding and reconstructing the  natural videos from brain fMRI signals using deep learning. I am extending the [Deep Image Prior](https://dmitryulyanov.github.io/deep_image_prior) and using it to
- Constrain the reconstructions in the natural and temporal coherence manifold.
- Understand the representations in Deep Neural Networks and brain.
- Probe unlearnt priors by the virtue of the architecture.
