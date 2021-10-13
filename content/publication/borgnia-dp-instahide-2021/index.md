---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DP-InstaHide: Provably Defusing Poisoning and Backdoor Attacks with Differentially
  Private Data Augmentations'
subtitle: ''
summary: ''
authors:
- Eitan Borgnia
- Jonas Geiping
- Valeriia Cherepanova
- Liam Fowl
- Arjun Gupta
- Amin Ghiasi
- Furong Huang
- Micah Goldblum
- Tom Goldstein
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Computer Science - Cryptography and Security"'
- '"Computer Science - Machine Learning"'
categories: []
date: '2021-03-01'
lastmod: 2021-05-31T15:10:53+02:00
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
publishDate: '2021-10-11T22:01:23.203519Z'
publication_types:
- '2'
abstract: Data poisoning and backdoor attacks manipulate training data to induce security
  breaches in a victim model. These attacks can be provably deflected using differentially
  private (DP) training methods, although this comes with a sharp decrease in model
  performance. The InstaHide method has recently been proposed as an alternative to
  DP training that leverages supposed privacy properties of the mixup augmentation,
  although without rigorous guarantees. In this work, we show that strong data augmentations,
  such as mixup and random additive noise, nullify poison attacks while enduring only
  a small accuracy trade-off. To explain these finding, we propose a training method,
  DP-InstaHide, which combines the mixup regularizer with additive noise. A rigorous
  analysis of DP-InstaHide shows that mixup does indeed have privacy advantages, and
  that training with k-way mixup provably yields at least k times stronger DP guarantees
  than a naive DP mechanism. Because mixup (as opposed to noise) is beneficial to
  model performance, DP-InstaHide provides a mechanism for achieving stronger empirical
  performance against poisoning attacks than other known DP methods.
publication: '*arXiv:2103.02079 [cs]*'
---
