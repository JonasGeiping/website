---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'MetaPoison: Practical General-Purpose Clean-Label Data Poisoning'
subtitle: ''
summary: ''
authors:
- W. Ronny Huang
- Jonas Geiping
- Liam Fowl
- Gavin Taylor
- Tom Goldstein
tags:
- '"Computer Science - Artificial Intelligence"'
- '"Computer Science - Computer Vision and Pattern Recognition"'
- '"Computer Science - Cryptography and Security"'
- '"Computer Science - Machine Learning"'
- '"Statistics - Machine Learning"'
categories: []
date: '2020-04-01'
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
publishDate: '2020-09-19T18:47:35.248442Z'
publication_types:
- 2
abstract: 'Data poisoning--the process by which an attacker takes control of a model
  by making imperceptible changes to a subset of the training data--is an emerging
  threat in the context of neural networks. Existing attacks for data poisoning have
  relied on hand-crafted heuristics. Instead, we pose crafting poisons more generally
  as a bi-level optimization problem, where the inner level corresponds to training
  a network on a poisoned dataset and the outer level corresponds to updating those
  poisons to achieve a desired behavior on the trained model. We then propose MetaPoison,
  a first-order method to solve this optimization quickly. MetaPoison is effective:
  it outperforms previous clean-label poisoning methods by a large margin under the
  same setting. MetaPoison is robust: its poisons transfer to a variety of victims
  with unknown hyperparameters and architectures. MetaPoison is also general-purpose,
  working not only in fine-tuning scenarios, but also for end-to-end training from
  scratch with remarkable success, e.g. causing a target image to be misclassified
  90% of the time via manipulating just 1% of the dataset. Additionally, MetaPoison
  can achieve arbitrary adversary goals not previously possible--like using poisons
  of one class to make a target image don the label of another arbitrarily chosen
  class. Finally, MetaPoison works in the real-world. We demonstrate successful data
  poisoning of models trained on Google Cloud AutoML Vision. Code and premade poisons
  are provided at https://github.com/wronnyhuang/metapoison'
publication: '*arXiv:2004.00225 [cs, stat]*'
---
