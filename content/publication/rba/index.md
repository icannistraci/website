---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Foundation Models on a Budget: Approximating Blocks in Large Vision Models'
subtitle: ''
summary: 'Under Revision'
authors:
- admin
- Simone Antonelli
- Emanuele Palumbo
- Thomas M. Sutter
- Emanuele Rodolà
- Bastian Rieck
- Julia E. Vogt
tags: []
categories: []
date: '2024-10-07'
lastmod: 2025-05-27
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
publishDate: '2024-10-11'
publication_types:
- '3'
abstract: 'Foundation Models have shown impressive performance in various tasks and domains, yet they require massive computational resources, raising concerns about accessibility and sustainability. Previous attempts to reduce foundation model size fall short of fully addressing the problem, as they end up increasing computational load through additional training steps. Recent works reveal that deep neural networks exhibit internal representation similarities. While inter-network similarities have enabled techniques such as model stitching and merging, intra-network similarities remain underexplored for improving efficiency. In this paper, we propose Transformer Blocks Approximation (TBA), a novel method that leverages intra-network similarities to identify and approximate transformer blocks in large vision models. TBA replaces these blocks using lightweight, closed-form transformations, without retraining or fine-tuning the rest of the model. The proposed method reduces the number of parameters while having minimal impact on the downstream task. We validate the effectiveness and generalizability of TBA through extensive experiments across multiple datasets (e.g., Imagenet-1k and CIFAR100) and state-of-the-art pretrained vision models (e.g, ViT, DiNO-v2, and DEiT).'
publication: ''
links:
- name: URL
  url : https://arxiv.org/abs/2410.04941
---
