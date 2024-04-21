---
author: "**Riccardo Marin**, Enric Corona, Gerard Pons-Moll"
categories:
- Conference
date: "2024-04-20"
date_end: ""
draft: false
event:  ArXiv.
event_url: 
excerpt: We propose a novel localized Neural Field (LoVD), the first self-supervised task for tuning neural fields (INT), and an efficient (takes less than a minute) scalable registration pipeline (NSR), that works with out-of-distribution data (partial point clouds, clutter, different poses, ...).
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
  url: https://github.com/riccardomarin/NICP
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Aligning a template to 3D human point clouds is a long-standing problem crucial for tasks like animation, reconstruction, and enabling supervised learning pipelines. Recent data-driven methods leverage predicted surface correspondences; however, they are not robust to varied poses, identities, or noise. In contrast, industrial solutions often rely on expensive manual annotations or multi-view capturing systems. Recently, neural fields have shown promising results. Still, their purely data-driven and extrinsic nature does not incorporate any guidance toward the target surface, often resulting in a trivial misalignment of the template registration. Currently, no method can be considered the standard for 3D Human registration, limiting the scalability of downstream applications. In this work, we propose NSR, a pipeline that, for the first time, generalizes and scales across thousands of shapes and more than ten different data sources. Our essential contribution is NICP, an ICP-style self-supervised task tailored to neural fields. NICP takes a few seconds, is self-supervised, and works out of the box on pre-trained neural fields. We combine it with a localized Neural Field trained on a large MoCap dataset. NSR achieves the state of the art over public benchmarks, and the release of its code and checkpoints will provide the community with a powerful tool useful for many downstream tasks like dataset alignments, cleaning, or asset animation."
title: "NICP: Neural ICP for 3D Human Registration at Scale"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
