---
author: "**Riccardo Marin**, Enric Corona, Gerard Pons-Moll"
categories:
- Conference
date: "2023-12-22"
date_end: ""
draft: false
event:  ArXiv, 2023.
event_url: 
excerpt: We propose a novel localized Neural Field (LoVD), the first self-supervised task for tuning neural fields (INT), and an efficient (takes less than a minute) registration pipeline (INLoVD), that works with out-of-distribution data (partial point clouds, clutter, different poses, ...).
featured: true
layout: single
links:
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://arxiv.org/abs/2312.14024
- icon: github
  icon_pack: fab
  name: code
  url: /talk/23-GeomAware/
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Aligning a template to 3D human point clouds is a long-standing problem crucial for tasks like animation, reconstruction, and enabling supervised learning pipelines. Recent data-driven methods leverage predicted surface correspondences; however, they are not robust to varied poses or distributions. In contrast, industrial solutions often rely on expensive manual annotations or multi-view capturing systems. Recently, neural fields have shown promising results, but their purely data-driven nature lacks geometric awareness, often resulting in a trivial misalignment of the template registration. In this work, we propose two solutions: LoVD, a novel neural field model that predicts the direction towards the localized SMPL vertices on the target surface; and INT, the first self-supervised task dedicated to neural fields that, at test time, refines the backbone, exploiting the target geometry. We combine them into INLoVD, a robust 3D Human body registration pipeline trained on a large MoCap dataset. INLoVD is efficient (takes less than a minute), solidly achieves the state of the art over public benchmarks, and provides unprecedented generalization on out-of-distribution data. We will release code and checkpoints."
title: "Geometric Awareness in Neural Fields for 3D Human Registration"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
