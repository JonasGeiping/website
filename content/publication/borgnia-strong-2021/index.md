---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Strong Data Augmentation Sanitizes Poisoning and Backdoor Attacks Without an
  Accuracy Tradeoff
subtitle: ''
summary: ''
authors:
- Eitan Borgnia
- Valeriia Cherepanova
- Liam Fowl
- Amin Ghiasi
- Jonas Geiping
- Micah Goldblum
- Tom Goldstein
- Arjun Gupta
tags:
- '"Adversarial Attacks"'
- '"Backdoor Attacks"'
- '"Conferences"'
- '"Data Augmentation"'
- '"Data models"'
- '"Data Poisoning"'
- '"Differential Privacy"'
- '"Industries"'
- '"Machine learning"'
- '"Signal processing"'
- '"Toxicology"'
- '"Training data"'
categories: []
date: '2021-06-01'
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
publishDate: '2021-10-11T22:01:23.459845Z'
publication_types:
- '1'
abstract: Data poisoning and backdoor attacks manipulate victim models by maliciously
  modifying training data. In light of this growing threat, a recent survey of industry
  professionals revealed heightened fear in the private sector regarding data poisoning.
  Many previous defenses against poisoning either fail in the face of increasingly
  strong attacks, or they significantly degrade performance. However, we find that
  strong data augmentations, such as mixup and CutMix, can significantly diminish
  the threat of poisoning and backdoor attacks without trading off performance. We
  further verify the effectiveness of this simple defense against adaptive poisoning
  methods, and we compare to baselines including the popular differentially private
  SGD (DP-SGD) defense. In the context of backdoors, CutMix greatly mitigates the
  attack while simultaneously increasing validation accuracy by 9%.
publication: '*ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech
  and Signal Processing (ICASSP)*'
doi: 10.1109/ICASSP39728.2021.9414862
---
