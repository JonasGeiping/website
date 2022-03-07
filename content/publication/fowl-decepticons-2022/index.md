---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Decepticons: Corrupted Transformers Breach Privacy in Federated Learning for
  Language Models'
subtitle: ''
summary: ''
authors:
- Liam Fowl
- Jonas Geiping
- Steven Reich
- Yuxin Wen
- Wojtek Czaja
- Micah Goldblum
- Tom Goldstein
tags:
- Computer Science - Computation and Language
- Computer Science - Cryptography and Security
- Computer Science - Machine Learning
categories: []
date: '2022-01-01'
lastmod: 2022-03-07T13:07:32-05:00
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
publishDate: '2022-03-07T18:07:32.394857Z'
publication_types:
- '2'
abstract: A central tenet of Federated learning (FL), which trains models without
  centralizing user data, is privacy. However, previous work has shown that the gradient
  updates used in FL can leak user information. While the most industrial uses of
  FL are for text applications (e.g. keystroke prediction), nearly all attacks on
  FL privacy have focused on simple image classifiers. We propose a novel attack that
  reveals private user text by deploying malicious parameter vectors, and which succeeds
  even with mini-batches, multiple users, and long sequences. Unlike previous attacks
  on FL, the attack exploits characteristics of both the Transformer architecture
  and the token embedding, separately extracting tokens and positional embeddings
  to retrieve high-fidelity text. This work suggests that FL on text, which has historically
  been resistant to privacy attacks, is far more vulnerable than previously thought.
publication: '*arXiv:2201.12675 [cs]*'
links:
- name: arXiv
  url: https://arxiv.org/abs/2201.12675
- name: URL
  url: http://arxiv.org/abs/2201.12675
---
