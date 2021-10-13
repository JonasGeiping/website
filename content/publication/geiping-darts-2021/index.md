---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DARTS for Inverse Problems: A Study on Hyperparameter Sensitivity'
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Jovita Lukasik
- Margret Keuper
- Michael Moeller
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Computer Science - Machine Learning"'
categories: []
date: '2021-08-01'
lastmod: 2021-10-11T18:01:25-04:00
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
publishDate: '2021-10-11T22:01:25.233120Z'
publication_types:
- '2'
abstract: 'Differentiable architecture search (DARTS) is a widely researched tool
  for neural architecture search, due to its promising results for image classification.
  The main benefit of DARTS is the effectiveness achieved through the weight-sharing
  one-shot paradigm, which allows efficient architecture search. In this work, we
  investigate DARTS in a systematic case study of inverse problems, which allows us
  to analyze these potential benefits in a controlled manner. Although we demonstrate
  that the success of DARTS can be extended from image classification to reconstruction,
  our experiments yield three fundamental difficulties in the evaluation of DARTS-based
  methods: First, the results show a large variance in all test cases. Second, the
  final performance is highly dependent on the hyperparameters of the optimizer. And
  third, the performance of the weight-sharing architecture used during training does
  not reflect the final performance of the found architecture well. Thus, we conclude
  the necessity to 1) report the results of any DARTS-based methods from several runs
  along with its underlying performance statistics, 2) show the correlation of the
  training and final architecture performance, and 3) carefully consider if the computational
  efficiency of DARTS outweighs the costs of hyperparameter optimization and multiple
  runs.'
publication: '*arXiv:2108.05647 [cs]*'
---
