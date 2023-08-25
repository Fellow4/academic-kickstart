---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Proximal Algorithms for Smoothed Online Convex Optimization with Predictions"
authors: ["Spandan Senapati", "Ashwin Shenai", "Ketan Rajawat"]
date: 2023-08-07
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-12-27T20:39:46+05:30

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proximal Algorithms for Smoothed Online Convex Optimization with Predictions"
publication_short: "IEEE Transactions on Signal Processing"

abstract: "We consider a smoothed online convex optimization (SOCO) problem with predictions, where the learner has access to a finite lookahead window of time-varying stage costs, but suffers a switching cost for changing its actions at each stage. Based on the Alternating Proximal Gradient Descent (APGD) framework, we develop Receding Horizon Alternating Proximal Descent (RHAPD) for proximable, non-smooth and strongly convex stage costs, and RHAPD-Smooth (RHAPD-S) for non-proximable, smooth and strongly convex stage costs. In addition to outperforming gradient descent-based algorithms, while maintaining a comparable runtime complexity, our proposed algorithms also allow us to solve a wider range of problems. We provide theoretical upper bounds on the dynamic regret achieved by the proposed algorithms, which decay exponentially with the length of the lookahead window. The performance of the presented algorithms is empirically demonstrated via numerical experiments on non-smooth regression, dynamic trajectory tracking, and economic power dispatch problems."

# Summary. An optional shortened abstract.
summary: "Short summary: We propose alternating proximal gradient descent based-algorithms for solving the problem of smoothed online convex optimization (for both smooth and non-smooth stage costs $f_{t}$) with predictions. The proposed algorithms allow us to solve a wider range of problems at a low computational cost and have similar theoretical guarantees as the existing gradient descent-based algorithms for smooth stage costs, while outperforming them on a number of numerical experiments."

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

url_pdf: https://arxiv.org/abs/2212.04459
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
