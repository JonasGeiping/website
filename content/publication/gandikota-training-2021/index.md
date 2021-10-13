---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Training or Architecture? How to Incorporate Invariance in Neural Networks
subtitle: ''
summary: ''
authors:
- Kanchana Vaishnavi Gandikota
- Jonas Geiping
- Zorah Lähner
- Adam Czapli\ŉski
- Michael Moeller
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
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
publishDate: '2021-10-11T22:01:24.505766Z'
publication_types:
- '2'
abstract: Many applications require the robustness, or ideally the invariance, of
  a neural network to certain transformations of input data. Most commonly, this requirement
  is addressed by either augmenting the training data, using adversarial training,
  or defining network architectures that include the desired invariance automatically.
  Unfortunately, the latter often relies on the ability to enlist all possible transformations,
  which make such approaches largely infeasible for infinite sets of transformations,
  such as arbitrary rotations or scaling. In this work, we propose a method for provably
  invariant network architectures with respect to group actions by choosing one element
  from a (possibly continuous) orbit based on a fixed criterion. In a nutshell, we
  intend to 'undo' any possible transformation before feeding the data into the actual
  network. We analyze properties of such approaches, extend them to equivariant networks,
  and demonstrate their advantages in terms of robustness as well as computational
  efficiency in several numerical examples. In particular, we investigate the robustness
  with respect to rotations of images (which can possibly hold up to discretization
  artifacts only) as well as the provable rotational and scaling invariance of 3D
  point cloud classification.
publication: '*arXiv:2106.10044 [cs]*'
---
