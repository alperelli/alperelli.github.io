---
title: "Multi-channel Convolutional Analysis Operator Learning for Dual-Energy CT Reconstruction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Suxer Alfonso Garcia
- Alexandre Bousse
- Jean-Pierre Tasu
- Nikolaos Efthimiadis
- Dimitris Visvikis

# Author notes (optional)

date: "2022-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Physics in Medicine & Biology
publication_short: In Physics in Medicine & Biology

abstract: Objective. Dual-energy computed tomography (DECT) has the potential to improve contrast, reduce artifacts and the ability to perform material decomposition in advanced imaging applications. The increased number or measurements results with a higher radiation dose and it is therefore essential to reduce either number of projections per energy or the source X-ray intensity, but this makes tomographic reconstruction more ill-posed. Approach. We developed the multi-channel convolutional analysis operator learning (MCAOL) method to exploit common spatial features within attenuation images at different energies and we propose an optimization method which jointly reconstructs the attenuation images at low and high energies with a mixed norm regularization on the sparse features obtained by pre-trained convolutional filters through the convolutional analysis operator learning (CAOL) algorithm. Main results. Extensive experiments with simulated and real computed tomography (CT) data were performed to validate the effectiveness of the proposed methods and we reported increased reconstruction accuracy compared to CAOL and iterative methods with single and joint total-variation (TV) regularization. Significance. Qualitative and quantitative results on sparse-views and low-dose DECT demonstrate that the proposed MCAOL method outperforms both CAOL applied on each energy independently and several existing state-of-the-art model-based iterative reconstruction (MBIR) techniques, thus paving the way for dose reduction.

# Summary. An optional shortened abstract.
summary: We developed the multi-channel convolutional analysis operator learning (MCAOL) method to exploit common spatial features within attenuation images at different energies and we propose an optimization method which jointly reconstructs the attenuation images at low and high energies with a mixed norm regularization on the sparse features obtained by pre-trained convolutional filters through the convolutional analysis operator learning (CAOL) algorithm. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iopscience.iop.org/article/10.1088/1361-6560/ac4c32'
url_code: 'https://github.com/alperelli/MCAOL'
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
- MCAOL_CT

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: RED_Spectral_CT
---