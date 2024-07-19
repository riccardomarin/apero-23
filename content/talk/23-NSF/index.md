---
author: Yuxuan Xue, Bharat Lal Bhatnagar, **Riccardo Marin**, Nikolaos Sarafianos, Yuanlu Xu, Gerard Pons-Moll, Tony Tung 
categories:
- Conference
date: "2023-10-22"
date_end: ""
draft: false
event:  IEEE/CVF International Conference on Computer Vision (ICCV), 2023.
event_url: 
excerpt: The Neural Surface Fields (NSF) defines a Neural Field on the level set of an implicit representation, providing a continuous and flexible function representation on 3D geometries. We apply it in an avatarization pipeline, learning animatable avatars with pose-dependent deformations starting from a sparse set of partial depth views.
featured: true
layout: single
links:
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://yuxuan-xue.com/nsf/paper/ICCV2023_Yuxuan_NSF_arxiv-1.pdf
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/YuxuanSnow/NeuralSurfaceField
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Creating personalized and animatable 3D avatars is challenging, with real-world applications in gaming, virtual try-on, animation, and VR/XR. On the other hand, it is also a complex problem to infer cloth geometry and dynamics from sparse and monocular view data. Existing methods for modeling 3D humans from depth data have limitations in terms of computational efficiency, mesh coherency, and flexibility in resolution and topology. Reconstructing shapes using implicit functions and extracting explicit meshes per frame is computationally expensive and cannot ensure coherent meshes across frames. Conversely, predicting per-vertex deformations on a pre-designed human template with a discrete surface lacks flexibility in resolution and topology. To overcome these limitations, we propose a novel method NSF: Neural Surface Fields' for modeling 3D clothed humans. A distinctive aspect of NSF is that it defines a neural field solely on the base surface, enabling it to predict a continuous displacement field over the surface. To determine the shape of the base surface, our method fuses depth observations in a canonical space and learns a coarse geometry without high-frequency pose-dependent deformations. Compared to existing approaches, our method eliminates the expensive per-frame surface extraction while maintaining mesh coherency, and is capable of reconstructing meshes with arbitrary resolution without retraining."
title: "NSF: Neural Surface Fields for Human Modeling from Monocular Depth"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
