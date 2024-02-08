---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Infusing invariances in neural representations
subtitle: ''
summary: '**TAG-ML @ ICML 2023** (Extended Abstract)'
authors:
- admin
- Marco Fumero
- Luca Moschella
- Valentino Maiorca
- Emanuele Rodolà
tags: []
categories: []
date: '2023-06-16'
lastmod: 2023-10-02T:26:44
featured: false
draft: false
publication_short: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Center'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2023-06-12T:26:44'
publication_types:
- '3'
abstract: 'It has been observed that inner representations learned by different neural networks conceal structural similarities when the networks are trained under similar inductive biases. Exploring the geometric structure of latent spaces within these networks offers insights into the underlying similarity among different neural models and facilitates reasoning about the transformations that connect them. Identifying and estimating these transformations presents a challenging task, but it holds significant potential for various downstream tasks, including merging and stitching different neural architectures for model reuse. In this study, drawing on the geometrical structure of latent spaces, we show how it is possible to define representations that incorporate invariances to the targeted transformations in a single framework. We experimentally analyze how inducing different invariances in the representations affects downstream performances on classification and reconstruction tasks, suggesting that the classes of transformations that relate independent latent spaces depend on the task at hand. We analyze models in a variety of settings including different initializations, architectural changes, and trained on multiple modalities (e.g., text, images), testing our framework on 8 different benchmarks.'
publication: '2nd Annual TAG in Machine Learning @ ICML 2023'
links:
- name: URL
  url : https://openreview.net/forum?id=mCm4iiNoNc
---
