---
title: "Compressive Computed Tomography Reconstruction through Denoising Approximate Message Passing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Michael Lexa
- Ali Can
- Mike E Davies

# Author notes (optional)

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: SIAM Journal on Imaging Sciences
publication_short: In SIAM Journal on Imaging Sciences

abstract: X-ray computed tomography (CT) reconstruction from a sparse number of views is a useful way to reduce either the radiation dose or the acquisition time, for example in fixed-gantry CT systems; however, this results in an ill-posed inverse problem whose solution is typically computationally demanding. Approximate message passing (AMP) techniques represent the state of the art for solving undersampling compressed sensing problems with random linear measurements, but there are still not clear solutions on how AMP should be modified and how it performs with real world problems. This paper investigates the question of whether we can employ an AMP framework for real sparse view CT imaging. The proposed algorithm for approximate inference in tomographic reconstruction incorporates a number of advances from within the AMP community, resulting in the denoising generalized approximate message passing CT algorithm (D-GAMP-CT). Specifically, this exploits the use of sophisticated image denoisers to regularize the reconstruction. While in order to reduce the probability of divergence the (Radon) system and the Poisson nonlinear noise model are treated separately, exploiting the existence of efficient preconditioners for the former and the generalized noise modeling in GAMP for the latter. Experiments with simulated and real CT baggage scans confirm that the performance of the proposed algorithm outperforms statistical CT optimization solvers.

# Summary. An optional shortened abstract.
summary: This paper investigates the question of whether we can employ an AMP framework for real sparse view CT imaging. The proposed algorithm for approximate inference in tomographic reconstruction incorporates a number of advances from within the AMP community, resulting in the denoising generalized approximate message passing CT algorithm (D-GAMP-CT).

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://iopscience.iop.org/article/10.1088/1361-6560/ac4c32'
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
- AMP_imaging

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: RED_Spectral_CT
---