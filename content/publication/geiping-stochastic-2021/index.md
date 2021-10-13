---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Stochastic Training Is Not Necessary for Generalization
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Micah Goldblum
- Phillip E. Pope
- Michael Moeller
- Tom Goldstein
tags:
- '"Computer Science - Machine Learning"'
- '"Mathematics - Optimization and Control"'
categories: []
date: '2021-09-01'
lastmod: 2021-10-11T18:01:27-04:00
featured: True
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-10-11T22:01:27.067457Z'
publication_types:
- '2'
abstract: It is widely believed that the implicit regularization of stochastic gradient
  descent (SGD) is fundamental to the impressive generalization behavior we observe
  in neural networks. In this work, we demonstrate that non-stochastic full-batch
  training can achieve strong performance on CIFAR-10 that is on-par with SGD, using
  modern architectures in settings with and without data augmentation. To this end,
  we utilize modified hyperparameters and show that the implicit regularization of
  SGD can be completely replaced with explicit regularization. This strongly suggests
  that theories that rely heavily on properties of stochastic sampling to explain
  generalization are incomplete, as strong generalization behavior is still observed
  in the absence of stochastic sampling. Fundamentally, deep learning can succeed
  without stochasticity. Our observations further indicate that the perceived difficulty
  of full-batch training is largely the result of its optimization properties and
  the disproportionate time and effort spent by the ML community tuning optimizers
  and hyperparameters for small-batch training.
publication: '*arXiv:2109.14119 null*'
---
