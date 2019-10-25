---
title: "Variational Bayesian Inference for Traffic Estimation and Prediction using Tensor Decomposition"
subtitle: ""
summary: ""
authors: []
tags: ["Bayesian Machine Learning", "Deep Learning"]
categories: []
date: 2019-05-08T21:50:19+05:29
lastmod: 2019-09-08T21:50:19+05:30
featured: false
draft: false

external_link : "https://github.com/Fellow4/Robust-Streaming-Tensor-Factorization"


# Featured image
# To use, add an image named featured.jpg/png to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. projects = ["internal-project"] references content/project/deep-learning/index.md.
#   Otherwise, set projects = [].
projects: []
---
Read and understood a paper by Cole Hawkins and Zheng Zhang on Tensor Decomposition using Variational Inference.Used a Tensor based model and applied Variational Inference to model the problem of Traffic Estimation and Prediction. Explored the mathematics behind Tensors, Low Rank Decompostion etc. Studied a paper on Bayesian Subspace Filtering by Ketan Rejawat. Derived a method in which temporal components follow a Markov Chain and non-temporal components is expressed in terms of a CP decomposition of Tensors. Currently implementing the model to Traffic4cast challenge data set by HERE Technologies in association with IARAI and hope to make a successful submission. Also exploring techniques such as LDL Decomposition to reduce the Time Complexity of our computations for taking Matrix Inversions which is very important for fast predictions.