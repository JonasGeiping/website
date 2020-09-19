---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Piecewise Rigid Scene Flow with Implicit Motion Segmentation
subtitle: ''
summary: ''
authors:
- Andreas Görlitz
- Jonas Geiping
- Andreas Kolb
tags:
- '"constant rigid motion"'
- '"ill-conditioned problem"'
- '"image colour analysis"'
- '"image segmentation"'
- '"image sequences"'
- '"implicit motion segmentation estimation approach"'
- '"joint energy minimization problem"'
- '"L0 rigid motion regularization"'
- '"minimisation"'
- '"motion estimation"'
- '"observed scene"'
- '"piecewise rigid motion"'
- '"piecewise rigid scene flow techniques"'
- '"proximal primal-dual algorithm"'
- '"RGB-D images"'
- '"rotational motion parts"'
- '"scene flow estimation approach"'
- '"translational motion parts"'
- '"variational approach"'
categories: []
date: '2019-11-01'
lastmod: 2020-09-19T20:47:35+02:00
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
publishDate: '2020-09-19T18:47:35.182087Z'
publication_types:
- 1
abstract: In this paper, we introduce a novel variational approach to estimate the
  scene flow from RGB-D images. We regularize the ill-conditioned problem of scene
  flow estimation in a unified framework by enforcing piecewise rigid motion through
  decomposition into rotational and translational motion parts. Our model crucially
  regularizes these components by an L0 “norm”, thereby facilitating implicit motion
  segmentation in a joint energy minimization problem. Yet, we also show that this
  energy can be efficiently minimized by a proximal primal-dual algorithm. By implementing
  this approximate L0 rigid motion regularization, our scene flow estimation approach
  implicitly segments the observed scene of into regions of nearly constant rigid
  motion. We evaluate our joint scene flow and segmentation estimation approach on
  a variety of test scenarios, with and without ground truth data, and demonstrate
  that we outperform current scene flow techniques.
publication: '*2019 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)*'
doi: 10.1109/IROS40897.2019.8968018
---
