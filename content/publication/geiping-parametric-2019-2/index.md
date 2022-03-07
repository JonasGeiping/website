---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Parametric Majorization for Data-Driven Energy Minimization Methods
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Michael Moeller
tags: []
categories: []
date: '2019-01-01'
lastmod: 2022-03-07T13:07:35-05:00
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
publishDate: '2022-03-07T18:07:35.405238Z'
publication_types:
- '1'
abstract: Energy minimization methods are a classical tool in a multitude of computer
  vision applications. While they are interpretable and well-studied, their regularity
  assumptions are difficult to design by hand. Deep learning techniques on the other
  hand are purely data-driven, often provide excellent results, but are very difficult
  to constrain to predefined physical or safety-critical models. A possible combination
  between the two approaches is to design a parametric en- ergy and train the free
  parameters in such a way that minimizers of the energy correspond to desired solution
  on a set of training examples. Unfortunately, such formulations typically lead to
  bi-level optimization problems, on which common optimization algorithms are difficult
  to scale to modern requirements in data processing and efficiency. In this work,
  we present a new strategy to optimize these bi-level problems. We investigate surrogate
  single-level problems that majorize the target problems and can be implemented with
  existing tools, leading to efficient algorithms without collapse of the energy function.
  This framework of strategies enables new avenues to the training of parameterized
  energy minimization models from large data.
publication: '*Proceedings of the IEEE International Conference on Computer Vision*'
links:
- name: URL
  url: http://openaccess.thecvf.com/content_ICCV_2019/html/Geiping_Parametric_Majorization_for_Data-Driven_Energy_Minimization_Methods_ICCV_2019_paper.html
---
