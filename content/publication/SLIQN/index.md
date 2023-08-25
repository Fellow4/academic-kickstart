---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sharpened Lazy Incremental Quasi-Newton Method"
authors: ["Aakash Lahoti*", "Spandan Senapati*", "Ketan Rajawat", "Alec Koppel"]
date: 2023-05-26T20:39:46+05:30
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-05-26T20:39:46+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Sharpened Lazy Incremental Quasi-Newton Method"
publication_short: "(*) denotes equal contribution. Preprint. Under review"

abstract: "We consider the finite sum minimization of $n$ strongly convex and smooth functions with Lipschitz continuous Hessians in $d$ dimensions. In many applications where such problems arise, including maximum likelihood estimation, empirical risk minimization, and unsupervised learning, the number of observations $n$ is large, and it becomes necessary to use incremental or stochastic algorithms whose per-iteration complexity is independent of $n$. Of these, the incremental/stochastic variants of the Newton method exhibit superlinear convergence, but incur a per-iteration complexity of $O(d ^ 3)$, which may be prohibitive in large-scale settings. On the other hand, the incremental Quasi-Newton method incurs a per-iteration complexity of $O(d ^ 2)$ but its superlinear convergence rate has only been characterized asymptotically. This work puts forth the Sharpened Lazy Incremental Quasi-Newton (SLIQN) method that achieves the best of both worlds: an explicit superlinear convergence rate with a per-iteration complexity of $O(d ^ 2)$. Building upon the recently proposed Sharpened Quasi-Newton method, the proposed incremental variant incorporates a hybrid update strategy incorporating both classic and greedy BFGS updates. The proposed lazy update rule distributes the computational complexity between the iterations, so as to enable a per-iteration complexity of $O(d ^ 2)$. Numerical tests demonstrate the superiority of SLIQN over all other incremental and stochastic Quasi-Newton variants."

# Summary. An optional shortened abstract.
summary: "Short summary: For the finite sum minimization problem, we propose the sharpened lazy incremental quasi-newton (SLIQN) method which has a per-iteration complexity of $O(d ^ 2)$ and an explicit non-asymptotic superlinear convergence rate. To the best of our knowledge, SLIQN is the first algorithm with an $O(d ^ 2)$ complexity per-iteration and an explicit non-asymptotic rate."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2305.17283.pdf
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
