---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Online Convex Optimization with Switching Cost and Delayed Gradients"
authors: ["Spandan Senapati", "Rahul Vaze"]
date: 2023-08-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-08-01T00:00:00+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Online Convex Optimization with Switching Cost and Delayed Gradients"
publication_short: "IFIP PERFORMANCE 2023. Full paper: Elsevier Performance Evaluation; extended abstract to appear in the ACM SIGMETRICS Performance Evaluation Review"

abstract: 
# "We consider the \textit{online convex optimization (OCO)} problem with \textit{quadratic} and \textit{linear} switching cost in the \textit{limited information} setting, where an online algorithm can choose its action using only gradient information about the previous objective function. For $L$-smooth and $\mu$-strongly convex objective functions, we propose an online multiple gradient descent (OMGD) algorithm and show that its competitive ratio for the OCO problem with quadratic switching cost is at most $4(L + 5) + \frac{16(L + 5)}{\mu}$. The competitive ratio upper bound for OMGD is also shown to be order-wise tight in terms of $L,\mu$. In addition, we show that the competitive ratio of any online algorithm is $\max\{\Omega(L), \Omega(\frac{L}{\sqrt{\mu}})\}$ in the limited information setting when the switching cost is quadratic. We also show that the OMGD algorithm achieves the optimal (order-wise) dynamic regret in the limited information setting.
# For the linear switching cost, the competitive ratio upper bound of the OMGD algorithm is shown to depend on both the path length and the squared path length of the problem instance, in addition to \(L, \mu\), and is shown to be order-wise, the best competitive ratio any online algorithm can achieve. Consequently, we conclude that the optimal competitive ratio for the quadratic and linear switching costs are fundamentally different in the limited information setting."

# Summary. An optional shortened abstract.
summary: 
# "Short summary: We consider the problem of online convex optimization with switching cost, in the limited information setting, where an algorithm can take action $x_{t}$ using only information about the gradient of $f_{t - 1}$ at multiple points. We show a surprising fact: a simple projected gradient descent based algorithm is powerful enough and has similar theoretical guarantees as more sophisticated algorithms (which require even more information). We derive (almost matching) lower bounds for the problem and show a fundamental difference when the switching cost is quadratic vs linear."

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

url_pdf: https://arxiv.org/abs/2310.11880
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
