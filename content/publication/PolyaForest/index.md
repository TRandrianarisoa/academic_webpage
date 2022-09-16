---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Smoothing and adaptation of shifted Pólya Tree ensembles"
authors: ["Thibault Randrianarisoa"]
date: 2020-10-26T08:00:00+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-26T15:14:57+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Bernoulli"
publication_short: ""

abstract: "
Recently,  S. Arlot and R. Genuer have shown that a model of random forests outperforms its single-tree counterpart in 
the estimation of $\\alpha-$Hölder functions, $\\alpha\\leq2$. This backs up the idea that ensembles of tree estimators 
are smoother estimators than single trees. On the other hand, most positive optimality results on Bayesian tree-based 
methods assume that $\\alpha\\leq1$. Naturally, one wonders whether Bayesian counterparts of forest estimators are 
optimal on smoother classes, just like it has been observed for frequentist estimators for $\\alpha\\leq 2$.
We dwell on the problem of density estimation and introduce an ensemble estimator from the classical (truncated) Pólya 
tree construction in Bayesian nonparametrics. The resulting Bayesian forest estimator is shown to lead to optimal 
posterior contraction rates, up to logarithmic terms, for the Hellinger and $L^1$ distances on probability density 
functions on $[0;1)$ for arbitrary Hölder regularity $\\alpha>0$. This improves upon previous results for constructions 
related to the Pólya tree prior whose optimality was only proven in the case $\\alpha\\leq 1$. Also, we introduce an 
adaptive version of this new prior in the sense that it does not require the knowledge of $\\alpha$ to be defined and 
attain optimality."


# Summary. An optional shortened abstract.
summary: ""

tags: ["Bayesian nonparametrics", "ensemble", "forest", "Pólya Tree"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://projecteuclid.org/journals/bernoulli/volume-28/issue-4/Smoothing-and-adaptation-of-shifted-Pólya-tree-ensembles/10.3150/21-BEJ1426.short"
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
