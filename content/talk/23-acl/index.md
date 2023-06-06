---
author: Andrea Santilli, Silvio Severino, Emilian Postolache, Valentino Maiorca, Michele Mancusi, **Riccardo Marin**, Emanuele Rodolà
categories:
- Conference
date: "2023-05-20"
date_end: ""
draft: false
event:  The Annual Meeting of the Association for Computational Linguistics, ACL, 2023
event_url: 
excerpt: We propose a parallel decoding algorithm to speedup transformer inference for translation.
featured: true
layout: single
links:
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://gladia.di.uniroma1.it/publication/ipi/ipi.pdf
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/teelinsan/parallel-decoding
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Autoregressive decoding limits the efficiency of transformers for Machine Translation (MT). The community proposed specific network architectures and learning-based methods to solve this issue, which are expensive and require changes to the MT model, trading inference speed at the cost of the translation quality. In this paper, we propose to address the problem from the point of view of decoding algorithms, as a less explored but rather compelling direction. We propose to reframe the standard greedy autoregressive decoding of MT with a parallel formulation leveraging Jacobi and Gauss-Seidel fixed-point iteration methods for fast inference. This formulation allows to speed up existing models without training or modifications while retaining translation quality. We present three parallel decoding algorithms and test them on different languages and models showing how the parallelization introduces a speedup up to 38% w.r.t. the standard autoregressive decoding and nearly 2x when scaling the method on parallel resources. Finally, we introduce a decoding dependency graph visualizer (DDGviz) that let us see how the model has learned the conditional dependence between tokens and inspect the decoding procedure."
title: "Accelerating Transformer Inference for Translation via Parallel Decoding"

---

elo
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
eòlo
---

I'm really excited to give this talk! Stay tuned for video and slides.
asdasd