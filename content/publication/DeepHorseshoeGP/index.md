---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Deep Horseshoe Gaussian Processes"
authors: ["Ismaël Castillo", "Thibault Randrianarisoa"]
date: 2024-03-04T10:04:34-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2024-06-10T10:04:34-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Deep Horseshoe Gaussian Processes"
publication_short: "Deep HGP"

abstract: "Deep Gaussian processes have recently been proposed as natural objects to fit, similarly to deep neural 
networks, possibly complex features present in modern data samples, such as compositional structures. Adopting a 
Bayesian nonparametric approach, it is natural to use deep Gaussian processes as prior distributions, and use the 
corresponding posterior distributions for statistical inference. We introduce the deep Horseshoe Gaussian process 
Deep-HGP, a new simple prior based on deep Gaussian processes with a squared-exponential kernel, that in particular 
enables data-driven choices of the key lengthscale parameters. For nonparametric regression with random design, we show 
that the associated tempered posterior distribution recovers the unknown true regression curve optimally in terms of 
quadratic loss, up to a logarithmic factor, in an adaptive way. The convergence rates are simultaneously adaptive to 
both the smoothness of the regression function and to its structure in terms of compositions. The dependence of the 
rates in terms of dimension are explicit, allowing in particular for input spaces of dimension increasing with the 
number of observations."

# Summary. An optional shortened abstract.
summary: "Submitted"

tags: ["Bayesian nonparametrics", "Deep Gaussian processes", "multibandwidth Gaussian process priors", 
"fractional posteriors", "high-dimensional regression"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/2403.01737"
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
