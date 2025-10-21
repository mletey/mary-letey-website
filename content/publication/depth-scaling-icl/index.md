---
abstract: We study in-context learning (ICL) of linear regression in a deep linear self-attention model, characterizing how performance depends on various computational and statistical resources (width, depth, number of training steps, batch size and data per context). In a joint limit where data dimension, context length, and residual stream width scale proportionally, we analyze the limiting asymptotics for three ICL settings. (1) isotropic covariates and tasks (ISO), (2) fixed and structured covariance (FS), and (3) where covariances are randomly rotated and structured (RRS). For ISO and FS settings, we find that depth only aids ICL performance if context length is limited. Alternatively, in the RRS setting where covariances change across contexts, increasing the depth leads to significant improvements in ICL, even at infinite context length. This provides a new solvable toy model of neural scaling laws which depends on both width and depth of a transformer and predicts an optimal transformer shape as a function of compute. This toy model enables computation of exact asymptotics for the risk as well as derivation of powerlaws under source/capacity conditions for the ICL tasks.
draft: false
url_pdf: https://arxiv.org/pdf/2510.01098
publication_types:
  - "3"
authors:
  - Blake Bordelon
  - admin
  - Cengiz Pehlevan
author_notes:
publication: ""
featured: false
date: 2025-10-01T16:02:38.971Z
title: Theory of Scaling Laws for In-Context Regression: Depth, Width, Context and Time
image:
  filename: null
  focal_point: Smart
  preview_only: true
doi: https://doi.org/10.48550/arXiv.2510.01098
---
