---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Contributions to the theoretical analysis of statistical learning and uncertainty quantification methods"
event: "PhD Defence"
event_url: ""
location: Sorbonne Université (Campus Pierre et Marie Curie), room 16-26-209 (Paul Lévy)
address:
  street: 4, place Jussieu
  city: Paris
  region: 
  postcode: 75005
  country: France
  
abstract: "Modern data analysis provides scientists with statistical and machine learning algorithms with impressive performance.
In front of their extensive use to tackle problems of constantly growing complexity, there is a real need to understand
the conditions under which algorithms are successful or bound to fail. An additional objective is to gain 
insights into the design of new algorithmic methods able to tackle more innovative and challenging tasks. A natural
framework for developing a mathematical theory of these methods is nonparametric inference. This area of Statistics is 
concerned with inferences of unknown quantities of interest under minimal assumptions, less restrictive than classical 
(parametric) statistics. The common thread is infinite-dimensional statistical modeling of a parameter on the 
data-generating mechanism. This flexibility is all the more appealing as we seek reliable algorithms under a wide range
of settings, and the progress of data acquisition techniques results in massive and complex datasets. This last point 
prompts us to conduct an asymptotic analysis, which is a traditional approach to assessing the performance of learning 
procedures. In this thesis, we consider both problems of function estimation and uncertainty quantification.


The first class of algorithms we deal with are Bayesian tree-based methods. They are based on a ‘divide-and-conquer’ 
principle, partitioning a sample space to estimate the parameter locally. In regression, these methods include BCART and 
the renowned BART, the later being an ensemble of trees or a forest. In density estimation, the famous Pólya Tree prior 
exemplifies these methods and is the building block of a myriad of related constructions. We propose a new extension, DPA,
that is a ‘forest of PTs’ and is shown to attain minimax contraction rates adaptively in Hellinger distance for arbitrary 
Hölder regularities. Adaptive rates in the stronger supremum norm are also obtained for the flexible Optional Pólya Tree 
(OPT) prior, a BCART-type prior, for regularities smaller than one. Gaussian processes are another popular class of priors 
studied in Bayesian nonparametrics and Machine Learning. Motivated by the ever-growing size of datasets, we propose a new
horseshoe Gaussian process with the aim to adapt to leverage a data structure of smaller dimension. First, we derive minimax optimal
contraction rates for its tempered posterior. Secondly, deep Gaussian processes are Bayesian counterparts to the famous 
deep neural networks. We prove that, as a building block in such a deep framework, it also gives optimal adaptive rates 
under compositional structure assumptions on the parameter. As for uncertainty quantification (UQ), Bayesian methods are
often praised for the principled solution they offer with the definition of credible sets. We prove that OPT credible 
sets are confidence sets with good coverage and size (in supremum norm) under qualitative self-similarity conditions. 
Moreover, we conduct a theoretical study of UQ in Wasserstein distances Wp, uncovering a new phenomenon. In dimensions smaller than $4$, it is
possible to construct confidence sets whose $W_p$-radii, $p\\leq2$, adapt to any regularities (with no qualitative assumptions).
This starkly contrasts the usual Lp theory, where concessions always have to be made."
summary: My PhD defence will be held on the 28th of September, 2pm, in room 16-26-209 (Paul Lévy) of Campus Pierre et Marie Curie (Sorbonne Université).

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-09-28T14:00:00+02:00
date_end: 2022-09-28T18:00:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2022-09-16T17:33:48+02:00

authors: ["Thibault Randrianarisoa"]
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
