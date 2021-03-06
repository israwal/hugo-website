---
title: Intervertebral Disc Segmentation Using U-Net
summary: Intervertebral Discs were segmented from spine fMRI data of 1,000 individuals using U-Net. With an F1 score of 94.1%, I achieved results comparable with the state-of-the-art literature.
tags:
- Machine Learning
- Computer Vision
date: "2020-07-01"

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
show_date: false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

**Status**: Completed (May 2020 - Jul 2020)


This project was completed as part of my summer internship at [Laboratory for Orthopaedic Biomechanics](https://orthobiomech.ethz.ch/), ETH Zurich, under the guidance of Dr. Jonas Widmer. I contributed to the image segmentation component of a larger pipeline for automatic analysis of spine MRI to identify spinal defects. Particularly, I was involved in the segmentation of intervertebral disc. I compared different variants of U-Net (viz. vanilla, skip connection, inception modules etc.) for the task. The best model (inception U-Net with skip connections) achieved a dice score of 94.1%, and the overall segmentation pipeline scored 91.8%, which is competitive with the state-of-the-art approaches.
