---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Variational Gaussian processes for linear inverse problems"
authors: ["Thibault Randrianarisoa", "Botond Szabó"]
date: 2023-12-15T09:56:44-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-10T09:56:44-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Variational Gaussian processes for linear inverse problems"
publication_short: ""

abstract: "
By now Bayesian methods are routinely used in practice for solving inverse problems. In inverse problems the parameter 
or signal of interest is observed only indirectly, as an image of a given map, and the observations are typically 
further corrupted with noise. Bayes offers a natural way to regularize these problems via the prior distribution and 
provides a probabilistic solution, quantifying the remaining uncertainty in the problem. However, the computational 
costs of standard, sampling based Bayesian approaches can be overly large in such complex models. Therefore, in practice
 variational Bayes is becoming increasingly popular. Nevertheless, the theoretical understanding of these methods is 
 still relatively limited, especially in context of inverse problems. In our analysis we investigate variational 
 Bayesian methods for Gaussian process priors to solve linear inverse problems. We consider both mildly and severely 
 ill-posed inverse problems and work with the popular inducing variable variational Bayes approach proposed by Titsias 
 [Titsias, 2009]. We derive posterior contraction rates for the variational posterior in general settings and show that 
 the minimax estimation rate can be attained by correctly tunned procedures. As specific examples we consider a 
 collection of inverse problems including the heat equation, Volterra operator and Radon transform and inducing variable
  methods based on population and empirical spectral features.
"

# Summary. An optional shortened abstract.
summary: " Advances in Neural Information Processing Systems 36 (NeurIPS 2023)"

tags: ["Variational Bayes", "Inverse Problems", "Gaussian Processes", "Inducing points"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://proceedings.neurips.cc/paper_files/paper/2023/file/5c25c15b5b2fd386ab188a918e54c7d5-Paper-Conference.pdf"
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

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
slides: ""
---
