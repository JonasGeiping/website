---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Adversarial Examples Make Strong Poisons
subtitle: ''
summary: ''
authors:
- Liam Fowl
- Micah Goldblum
- Ping-yeh Chiang
- Jonas Geiping
- Wojtek Czaja
- Tom Goldstein
tags:
- '"Computer Science - Cryptography and Security"'
- '"Computer Science - Machine Learning"'
categories: []
date: '2021-06-01'
lastmod: 2021-10-11T18:01:24-04:00
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
publishDate: '2021-10-11T22:01:23.983016Z'
publication_types:
- '2'
abstract: The adversarial machine learning literature is largely partitioned into
  evasion attacks on testing data and poisoning attacks on training data. In this
  work, we show that adversarial examples, originally intended for attacking pre-trained
  models, are even more effective for data poisoning than recent methods designed
  specifically for poisoning. Our findings indicate that adversarial examples, when
  assigned the original label of their natural base image, cannot be used to train
  a classifier for natural images. Furthermore, when adversarial examples are assigned
  their adversarial class label, they are useful for training. This suggests that
  adversarial examples contain useful semantic content, just with the ``wrong'' labels
  (according to a network, but not a human). Our method, adversarial poisoning, is
  substantially more effective than existing poisoning methods for secure dataset
  release, and we release a poisoned version of ImageNet, ImageNet-P, to encourage
  research into the strength of this form of data obfuscation.
publication: '*arXiv:2106.10807 [cs]*'
---
