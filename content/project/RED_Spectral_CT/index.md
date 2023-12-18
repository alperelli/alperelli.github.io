---
title: Regularized Stochastic Optimization by Denoising 
summary: 'The main challenges of the project are related to the fact that
biomedical image reconstruction requires to recover input data lying in an high-dimensional space and to leverage more sophisticated or
learned data-dependent priors which are needed since the estimation problem is generally ill-posed.'

tags:
- Stochastic image reconstruction
- Optimization
date: "2021-11-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 

image:
  caption: 'Photo by Papamakarios, Comparison of Modern Stochastic Optimization Algorithms, 2014'
  focal_point: Smart

url_code: "https://github.com/alperelli/Denoising-IHS"
url_pdf: "https://arxiv.org/pdf/2103.13909"
url_slides: ""
url_video: "https://www.ccppetmr.ac.uk/sites/www.ccppetmr.ac.uk/files/Perelli_Presentation_04Nov2019.pdf"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

To solve the image reconstruction problem in the high-dimensional setting, numerous first order solvers which leverage random numerical linear algebra have been deployed in order to reduce the per-iteration computational cost in different machine learning and imaging applications. Well established algorithms like Stochastic Gradient Descent (SGD), order subsets and Alternating Direction Method of Multiplier (ADMM) have gained considerably attention in spectral CT [22, 23]. Unfortunately, the iteration complexity of first order methods relies significantly on the condition number of the problem like SGD which has a sub-linear convergence rate to only a neighborhood of the solution. Instead, the information related to the curvature is decisive to improve the convergence by reducing the condition number and to obtain physical meaningful and accurate quantitative estimation. 

Therefore, accounting for a greedy selection of parameters and step-size is crucial to design first-order algorithms for imaging like CT image reconstruction. Deterministic second order methods for solving regularized optimization problems with Generalized Linear Models (GLM) have been widely studied but despite the superior, linear or super-linear, convergence rate of Newton methods compared to first order methods one weakness relies on the high computational cost of calculating the Hessian matrix in high dimensional imaging application.

In this project, a new family of second-order algorithm with application to statistical iterative material decomposition is developed which enjoys an improved accuracy and computation trade-off. We
propose a computational efficient quantitative estimation with second order and parameters-free methods based on randomized linear algebra and regularization induced by denoising. We exploit the recent development of randomized sketches and sub-sampling methods for the Hessian matrix to improve upon the computational cost-per-iteration.