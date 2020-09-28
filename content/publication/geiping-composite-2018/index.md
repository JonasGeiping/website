---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Composite Optimization by Nonconvex Majorization-Minimization
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Michael Moeller
tags:
- '"90C26; 90C06; 68U10; 32B20; 65K10; 47J06"'
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Mathematics - Numerical Analysis"'
- '"Mathematics - Optimization and Control"'
categories: []
date: '2018-01-01'
lastmod: 2020-09-19T20:47:34+02:00
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
publishDate: '2020-09-19T18:47:34.573689Z'
publication_types:
- 2
abstract: The minimization of a nonconvex composite function can model a variety of
  imaging tasks. A popular class of algorithms for solving such problems are majorization-minimization
  techniques which iteratively approximate the composite nonconvex function by a majorizing
  function that is easy to minimize. Most techniques, e.g., gradient descent, utilize
  convex majorizers in order to guarantee that the majorizer is easy to minimize.
  In our work we consider a natural class of nonconvex majorizers for these functions,
  and show that these majorizers are still sufficient for a globally convergent optimization
  scheme. Numerical results illustrate that by applying this scheme, one can often
  obtain superior local optima compared to previous majorization-minimization methods,
  when the nonconvex majorizers are solved to global optimality. Finally, we illustrate
  the behavior of our algorithm for depth superresolution from raw time-of-flight
  data.
publication: '*SIAM Journal on Imaging Sciences*'
doi: 10.1137/18M1171989
---
