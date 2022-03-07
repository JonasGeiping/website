---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "What Doesn't Kill You Makes You Robust(Er): Adversarial Training against Poisons\
  \ and Backdoors"
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Liam Fowl
- Gowthami Somepalli
- Micah Goldblum
- Michael Moeller
- Tom Goldstein
tags:
- Computer Science - Computer Vision and Pattern Recognition
- Computer Science - Cryptography and Security
- Computer Science - Machine Learning
categories: []
date: '2021-02-01'
lastmod: 2022-03-07T13:07:36-05:00
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
publishDate: '2022-03-07T18:07:35.906776Z'
publication_types:
- '2'
abstract: 'Data poisoning is a threat model in which a malicious actor tampers with
  training data to manipulate outcomes at inference time. A variety of defenses against
  this threat model have been proposed, but each suffers from at least one of the
  following flaws: they are easily overcome by adaptive attacks, they severely reduce
  testing performance, or they cannot generalize to diverse data poisoning threat
  models. Adversarial training, and its variants, is currently considered the only
  empirically strong defense against (inference-time) adversarial attacks. In this
  work, we extend the adversarial training framework to instead defend against (training-time)
  poisoning and backdoor attacks. Our method desensitizes networks to the effects
  of poisoning by creating poisons during training and injecting them into training
  batches. We show that this defense withstands adaptive attacks, generalizes to diverse
  threat models, and incurs a better performance trade-off than previous defenses.'
publication: '*arXiv:2102.13624 [cs]*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2102.13624
- name: URL
  url: http://arxiv.org/abs/2102.13624
---
