---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Witches' Brew: Industrial Scale Data Poisoning via Gradient Matching"
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Liam Fowl
- W. Ronny Huang
- Wojciech Czaja
- Gavin Taylor
- Michael Moeller
- Tom Goldstein
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Computer Science - Machine Learning"'
categories: []
date: '2020-09-01'
lastmod: 2020-09-08T20:33:30+02:00
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
publishDate: '2020-09-08T18:33:30.205215Z'
publication_types:
- 2
abstract: Data Poisoning attacks involve an attacker modifying training data to maliciouslycontrol
  a model trained on this data. Previous poisoning attacks against deep neural networks
  have been limited in scope and success, working only in simplified settings or being
  prohibitively expensive for large datasets. In this work, we focus on a particularly
  malicious poisoning attack that is both \"from scratch\" and\"clean label\", meaning
  we analyze an attack that successfully works against new, randomly initialized models,
  and is nearly imperceptible to humans, all while perturbing only a small fraction
  of the training data. The central mechanism of this attack is matching the gradient
  direction of malicious examples. We analyze why this works, supplement with practical
  considerations. and show its threat to real-world practitioners, finding that it
  is the first poisoning method to cause targeted misclassification in modern deep
  networks trained from scratch on a full-sized, poisoned ImageNet dataset. Finally
  we demonstrate the limitations of existing defensive strategies against such an
  attack, concluding that data poisoning is a credible threat, even for large-scale
  deep learning systems.
publication: '*ArXiv200902276 Cs*'
---
