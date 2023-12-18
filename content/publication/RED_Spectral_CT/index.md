---
title: "Regularization by Denoising Sub-Sampled Newton Method for Spectral CT Multi-Material Decomposition"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Martin S. Andersen

# Author notes (optional)

date: "2021-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Philosophical Transactions of Royal Society A
publication_short: In Philosophical Transactions of Royal Society A

abstract: Spectral Computed Tomography (CT) is an emerging technology that enables to estimate the concentration of basis materials within a scanned object by exploiting different photon energy spectra. In this work, we aim at efficiently solving a model-based maximum-a-posterior problem to reconstruct multimaterials images with application to spectral CT. In particular, we propose to solve a regularized optimization problem based on a plug-in image denoising function using a randomized second order method. By approximating the Newton step using a sketching of the Hessian of the likelihood function, it is possible to reduce the complexity while retaining the complex prior structure given by the data-driven regularizer. We exploit a non-uniform block sub-sampling of the Hessian with inexact but efficient Conjugate gradient updates that require only Jacobian-vector products for denoising term. Finally, we show numerical and experimental results for spectral CT materials decomposition. This article is part of the theme issue Synergistic tomographic image reconstruction (part 1).

# Summary. An optional shortened abstract.
summary: Spectral Computed Tomography (CT) is an emerging technology that enables to estimate the concentration of basis materials within a scanned object by exploiting different photon energy spectra. In this work, we aim at efficiently solving a model-based maximum-a-posterior problem to reconstruct multimaterials images with application to spectral CT. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1098/rsta.2020.0191'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- RED_Spectral_CT

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: RED_Spectral_CT
---

The implementation of the method and the CT dataset are available here. [Matlab code](https://github.com/alperelli/Denoising-IHS), [Dataset](https://zenodo.org/record/4482071#.YfPV3PvP2F4)
