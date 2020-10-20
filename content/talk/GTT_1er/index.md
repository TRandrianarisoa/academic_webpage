---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Smoothing of Bayesian forest estimators in density estimation"
event: "Groupe de travail des thésards du LPSM"
event_url: "https://www.lpsm.paris/agenda/seminaires-gdt/gtt/smoothing-bayesian-forest-estimators-density-estimation/"
location:
address:
  street:
  city:
  region:
  postcode:
  country:
summary:
abstract: "With CART regression trees, the values of the estimator in the leaf cells are equal to the mean of the observed 
data in each cell. Hence, once the tree structure is specified, this defines a histogram estimator. As a drawback, this 
limits its performance when the regression function $f_0$ to be recovered is $\alpha$-Hölder regular, with $\alpha > 1$. 
However, it has been noted that ensemble methods, defining a forest estimator, could generate a smoothing effect, 
improving over the convergence rate of single tree estimators.
We are going to see how such ideas translate into nonparametric Bayesian inference. Indeed, a popular prior distribution
 involving a tree structure and ßused in density estimation is the Pólya tree prior. So we will see how we can define prior
  distributions via forests of Pólya trees. First, these lead to nearly optimal contraction rates of the posterior distribution, 
  for any regularity $\alpha > 0$ of the true density $f_0$. Secondly, such priors can also be made adaptive to $\alpha > 0$. 
  This is a sought-after property of inference methods as this smoothness parameter is often unknown in practice.
  "

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2020-06-08T17:00:00+02:00
date_end: 2020-06-08T18:00:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2020-06-08T17:00:00+02:00

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:

url_code:
url_pdf:
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
