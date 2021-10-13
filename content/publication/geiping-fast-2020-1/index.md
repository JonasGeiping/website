---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Fast Convex Relaxations Using Graph Discretizations
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Fjedor Gaede
- Hartmut Bauermeister
- Michael Moeller
tags:
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Mathematics - Optimization and Control"'
categories: []
date: '2020-09-01'
lastmod: 2021-05-31T15:10:54+02:00
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
publishDate: '2021-10-11T22:01:25.474674Z'
publication_types:
- '1'
abstract: 'Matching and partitioning problems are fundamentals of computer vision
  applications with examples in multilabel segmentation, stereo estimation and optical-flow
  computation. These tasks can be posed as non-convex energy minimization problems
  and solved near-globally optimal by recent convex lifting approaches. Yet, applying
  these techniques comes with a significant computational effort, reducing their feasibility
  in practical applications. We discuss spatial discretization of continuous partitioning
  problems into a graph structure, generalizing discretization onto a Cartesian grid.
  This setup allows us to faithfully work on super-pixel graphs constructed by SLIC
  or Cut-Pursuit, massively decreasing the computational effort for lifted partitioning
  problems compared to a Cartesian grid, while optimal energy values remain similar:
  The global matching is still solved near-globally optimal. We discuss this methodology
  in detail and show examples in multi-label segmentation by minimal partitions and
  stereo estimation, where we demonstrate that the proposed graph discretization can
  reduce runtime as well as memory consumption of convex relaxations of matching problems
  by up to a factor of 10.'
publication: '*31st British Machine Vision Conference (BMVC 2020, Oral Presentation)*'
---
