---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Fishing for User Data in Large-Batch Federated Learning via Gradient Magnification
subtitle: ''
summary: ''
authors:
- Yuxin Wen
- Jonas Geiping
- Liam Fowl
- Micah Goldblum
- Tom Goldstein
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Cryptography and Security
- Computer Science - Machine Learning
categories: []
date: '2022-02-01'
lastmod: 2022-03-07T13:07:37-05:00
featured: true
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
publishDate: '2022-03-07T18:07:37.162605Z'
publication_types:
- '2'
abstract: Federated learning (FL) has rapidly risen in popularity due to its promise
  of privacy and efficiency. Previous works have exposed privacy vulnerabilities in
  the FL pipeline by recovering user data from gradient updates. However, existing
  attacks fail to address realistic settings because they either 1) require a `toy'
  settings with very small batch sizes, or 2) require unrealistic and conspicuous
  architecture modifications. We introduce a new strategy that dramatically elevates
  existing attacks to operate on batches of arbitrarily large size, and without architectural
  modifications. Our model-agnostic strategy only requires modifications to the model
  parameters sent to the user, which is a realistic threat model in many scenarios.
  We demonstrate the strategy in challenging large-scale settings, obtaining high-fidelity
  data extraction in both cross-device and cross-silo federated learning.
publication: '*arXiv:2202.00580 [cs]*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2202.00580
- name: URL
  url: http://arxiv.org/abs/2202.00580
---
