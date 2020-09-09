---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multiframe Motion Coupling for Video Super Resolution
subtitle: ''
summary: ''
authors:
- Jonas Geiping
- Hendrik Dirks
- Daniel Cremers
- Michael Moeller
tags: []
categories: []
date: '2018-01-01'
lastmod: 2020-09-08T20:33:30+02:00
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
publishDate: '2020-09-08T18:33:30.089344Z'
publication_types:
- 1
abstract: The idea of video super resolution is to use different view points of a
  single scene to enhance the overall resolution and quality. Classical energy minimization
  approaches first establish a correspondence of the current frame to all its neighbors
  in some radius and then use this temporal information for enhancement. In this paper,
  we propose the first variational super resolution approach that computes several
  super resolved frames in one batch optimization procedure by incorporating motion
  information between the high-resolution image frames themselves. As a consequence,
  the number of motion estimation problems grows linearly in the number of frames,
  opposed to a quadratic growth of classical methods and temporal consistency is enforced
  naturally.We use infimal convolution regularization as well as an automatic parameter
  balancing scheme to automatically determine the reliability of the motion information
  and reweight the regularization locally. We demonstrate that our approach yields
  state-of-the-art results and even is competitive with machine learning approaches.
publication: '*Energy Minimization Methods in Computer Vision and Pattern Recognition*'
doi: 10.1007/978-3-319-78199-0 _ 9
---
