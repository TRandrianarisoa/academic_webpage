---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "On Adaptive Confidence Sets for the Wasserstein Distances"
authors: ["Neil Deo", "Thibault Randrianarisoa"]
date: 2023-08-01T08:00:00+01:00
doi: "10.3150/22-BEJ1535"

# Schedule page publish date (NOT publication's date).
# publishDate: 2021-11-17T16:58:18+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bernoulli"
publication_short: ""

abstract: "
In the density estimation model, we investigate the problem of  constructing *adaptive honest confidence sets* 
with radius measured in Wasserstein distance $W_p$, $p\\geq1$, and for densities with unknown regularity measured on a 
Besov scale. As sampling domains, we focus on the $d-$dimensional torus $T^d$, in which case $1\\leq p\\leq 2$, 
and $R^d$, for which $p=1$. We identify necessary and sufficient conditions for the existence of adaptive 
confidence sets with diameters of the order of the regularity-dependent $W_p$-minimax estimation rate. Interestingly, 
it appears that the possibility of such adaptation of the diameter depends on the dimension of the underlying space. 
In low dimensions, $d\\leq 4$, adaptation to any regularity is possible. In higher dimensions, adaptation is possible 
if and only if the underlying regularities belong to some interval of width at least $d/(d-4)$. This contrasts with the 
usual $L_p-$theory where, independently of the dimension, adaptation requires regularities to lie in a small fixed-width
window. For configurations allowing these adaptive sets to exist, we explicitly construct confidence regions via the
method of risk estimation, centred at adaptive estimators. Those are the first results in a statistical approach to 
adaptive uncertainty quantification with Wasserstein distances. Our analysis and methods extend more globally to weak 
losses such as Sobolev norm distances with negative smoothness indices."

# Summary. An optional shortened abstract.
summary: "Bernoulli, 2023"

tags: ["Wasserstein distance", "Uncertainty Quantification", "Nonparametric confidence sets"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/abs/2111.08505"
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
  caption: "Median trees from Optional Pólya Tree posteriors"
  focal_point: "Smart"
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
