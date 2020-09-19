---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Witchcraft: Efficient PGD Attacks with Random Step Size'
subtitle: ''
summary: ''
authors:
- Ping-Yeh Chiang
- Jonas Geiping
- Micah Goldblum
- Tom Goldstein
- Renkun Ni
- Steven Reich
- Ali Shafahi
tags:
- '"Adversarial"'
- '"adversarial attacks"'
- '"Attack"'
- '"CIFAR"'
- '"classical PGD attack"'
- '"CNN"'
- '"gradient methods"'
- '"iterative FGSM-based methods"'
- '"iterative methods"'
- '"learning (artificial intelligence)"'
- '"neural nets"'
- '"neural networks"'
- '"PGD"'
- '"PGD attacks"'
- '"projected gradient descent"'
- '"random step size"'
- '"stochastic processes"'
- '"wide iterative stochastic crafting"'
- '"witchcraft"'
categories: []
date: '2020-05-01'
lastmod: 2020-09-19T20:47:34+02:00
featured: false
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
publishDate: '2020-09-19T18:47:34.424726Z'
publication_types:
- 1
abstract: State-of-the-art adversarial attacks on neural networks use expensive iterative
  methods and numerous random restarts from different initial points. Iterative FGSM-based
  methods without restarts trade off performance for computational efficiency because
  they do not adequately explore the image space and are highly sensitive to the choice
  of step size. We propose a variant of Projected Gradient Descent (PGD) that uses
  a random step size to improve performance without resorting to expensive random
  restarts. Our method, Wide Iterative Stochastic crafting (WITCHcraft), achieves
  results superior to the classical PGD attack on the CIFAR-10 and MNIST data sets
  but without additional computational cost. This simple modification of PGD makes
  crafting attacks more economical, which is important in situations like adversarial
  training where attacks need to be crafted in real time.
publication: '*ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)*'
doi: 10.1109/ICASSP40776.2020.9052930
---
