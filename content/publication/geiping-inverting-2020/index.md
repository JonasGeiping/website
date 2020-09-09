---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Inverting Gradients -- How Easy Is It to Break Privacy in Federated Learning?
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Hartmut Bauermeister
- Hannah Dröge
- Michael Moeller
tags: []
categories: []
date: '2020-03-01'
lastmod: 2020-09-08T20:33:30+02:00
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
publishDate: '2020-09-08T18:33:30.030756Z'
publication_types:
- 2
abstract: "The idea of federated learning is to collaboratively train a neural network\
  \ on a server. Each user receives the current weights of the network and in turns\
  \ sends parameter updates (gradients) based on local data. This protocol has been\
  \ designed not only to train neural networks data-efficiently, but also to provide\
  \ privacy benefits for users, as their input data remains on device and only parameter\
  \ gradients are shared. In this paper we show that sharing parameter gradients is\
  \ by no means secure: By exploiting a cosine similarity loss along with optimization\
  \ methods from adversarial attacks, we are able to faithfully reconstruct images\
  \ at high resolution from the knowledge of their parameter gradients, and demonstrate\
  \ that such a break of privacy is possible even for trained deep networks. Moreover,\
  \ we analyze the effects of architecture as well as parameters on the difficulty\
  \ of reconstructing the input image, prove that any input to a fully connected layer\
  \ can be reconstructed analytically independent of the remaining architecture, and\
  \ show numerically that even averaging gradients over several iterations or several\
  \ images does not protect the user's privacy in federated learning applications\
  \ in computer vision."
publication: '*ArXiv200314053 Cs*'
---
