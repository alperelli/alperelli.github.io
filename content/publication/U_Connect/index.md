---
title: "Uconnect: Synergistic Spectral CT Reconstruction With U-Nets Connecting the Energy Bins"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhihan Wang
- Alexandre Bousse
- Franck Vermet
- Jacques Froment
- Beatrice Vedel
- admin
- Jean-Pierre Tasu
- Dimitris Visvikis

# Author notes (optional)

date: "2023-11-01T00:00:00Z"
doi: "10.1109/TRPMS.2023.3330045"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Radiation and Plasma Medical Sciences
publication_short: In IEEE Transactions on Radiation and Plasma Medical Sciences

abstract: "Spectral computed tomography (CT) offers the possibility to reconstruct attenuation images at different energy levels, which can be then used for material decomposition. However, traditional methods reconstruct each energy bin individually and are vulnerable to noise. 

In this paper, we propose a novel synergistic method for spectral CT reconstruction, namely Uconnect. It utilizes trained convolutional neural networks (CNNs) to connect the energy bins to a latent image so that the full binned data is used synergistically. 

We experiment on two types of low-dose data: simulated and real patient data. Qualitative and quantitative analysis show that our proposed Uconnect outperforms state-of-art model-based iterative reconstruction (MBIR) techniques as well as CNN-based denoising"

# Summary. An optional shortened abstract.
summary: "In this paper, we propose a novel synergistic method for spectral CT reconstruction, namely Uconnect. It utilizes trained convolutional neural networks (CNNs) to connect the energy bins to a latent image so that the full binned data is used synergistically." 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/TRPMS.2023.3330045'

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
- U_Connect

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: RED_Spectral_CT
---

