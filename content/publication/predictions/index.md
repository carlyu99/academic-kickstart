---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "The Power of Predictions in Online Control"
authors:
  ["Chenkai Yu", "Guanya Shi", "Soon-Jo Chung", "Yisong Yue", "Adam Wierman"]
date: 2020-12-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-08-06T04:28:58-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Thirty-fourth Conference on Neural Information Processing Systems"
publication_short: "NeurIPS 2020"

abstract: "We study the impact of predictions in online Linear Quadratic Regulator control with both stochastic and adversarial disturbances in the dynamics. In both settings, we characterize the optimal policy and derive tight bounds on the minimum cost and dynamic regret. Perhaps surprisingly, our analysis shows that the conventional greedy MPC approach is a near-optimal policy in both stochastic and adversarial settings. Specifically, for length-$T$ problems, MPC requires only $O(\\log T)$ predictions to reach $O(1)$ dynamic regret, which matches (up to lower-order terms) our lower bound on the required prediction horizon for constant regret."

# Summary. An optional shortened abstract.
summary: ""

tags: [Control Theory, Online Algorithm]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
#   - name: Follow
#     url: https://twitter.com
#     icon_pack: fab
#     icon: twitter
links:
  - name: ZhiHu
    url: https://zhuanlan.zhihu.com/p/277415608
    icon_pack: fab
    icon: zhihu

url_pdf: https://arxiv.org/abs/2006.07569
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
