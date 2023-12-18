---
title: "Uconnect: Synergistic Spectral CT Reconstruction With U-Nets Connecting the Energy Bins"

summary: 'We propose a novel synergistic method for spectral CT reconstruction, namely Uconnect. It utilizes trained convolutional neural networks to connect the energy bins to a latent image so that the full binned data is used synergistically.'

tags:
- Spectral CT
date: "2023-10-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: 
  focal_point: Smart

url_slides: ""
url_pdf: "https://arxiv.org/abs/2311.00666"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Spectral computed tomography (CT) offers the possibility to reconstruct attenuation images at different energy levels, which can be then used for material decomposition. However, traditional methods reconstruct each energy bin individually and are vulnerable to noise. 

In this paper, we propose a novel synergistic method for spectral CT reconstruction, namely Uconnect. It utilizes trained convolutional neural networks (CNNs) to connect the energy bins to a latent image so that the full binned data is used synergistically. 

We experiment on two types of low-dose data: simulated and real patient data. Qualitative and quantitative analysis show that our proposed Uconnect outperforms state-of-art model-based iterative reconstruction (MBIR) techniques as well as CNN-based denoising