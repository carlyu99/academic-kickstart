---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Combining Model-Based and Model-Free Methods for Nonlinear Control: A Provably Convergent Policy Gradient Approach"
authors: ["Guannan Qu", "Chenkai Yu", "Steven Low", "Adam Wierman"]
date: 2020-06-12T15:03:01-07:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-06T15:03:01-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Model-free learning-based control methods have seen great success recently. However, such methods typically suffer from poor sample complexity and limited convergence guarantees. This is in sharp contrast to classical model-based control, which has a rich theory but typically requires strong modeling assumptions. In this paper, we combine the two approaches to achieve the best of both worlds. We consider a dynamical system with both linear and non-linear components and develop a novel approach to use the linear model to define a warm start for a model-free, policy gradient method. We show this hybrid approach outperforms the model-based controller while avoiding the convergence issues associated with model-free approaches via both numerical experiments and theoretical analyses, in which we derive sufficient conditions on the non-linear component such that our approach is guaranteed to converge to the (nearly) global optimal controller."

# Summary. An optional shortened abstract.
summary: ""

tags: [Learning, Control Theory]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/2006.07476
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
