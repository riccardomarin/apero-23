---
author: Lu Sang, Zehranaz Canfes, Dongliang Cao, **Riccardo Marin**, Florian Bernard, Daniel Cremers
categories:
- Conference
date: "2025-04-23"
date_end: ""
draft: false
event:  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025.
event_url: 
excerpt: We recover a 4D realistic deformation between two sparse unordered point clouds. After applying shape matching and registration methods to obtain rough and noisy correspondence, we leverage the theory of level-set methods to infer a deformation that is continuous and physically plausible. 
featured: true
layout: single
links:
- icon: archive
  icon_pack: fas
  name: Project Page
  url: https://4deform.github.io/
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://arxiv.org/pdf/2502.20208
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Sangluisme/4Deform
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Generating realistic intermediate shapes between non-rigidly deformed shapes is a challenging task in computer vision, especially with unstructured data (eg, point clouds) where temporal consistency across frames is lacking, and topologies are changing. Most interpolation methods are designed for structured data (ie, meshes) and do not apply to real-world point clouds. In contrast, our approach leverages neural implicit representation (NIR) to enable free-topology changing shape deformation. Unlike previous mesh-based methods, which model learns vertex-based deformation fields, our method learns a continuous velocity field in Euclidean space, making it suitable for less structured data such as point clouds. Additionally, our method does not require intermediate-shape supervision during training; instead, we incorporate physical and geometrical constraints to regularize the velocity field. We reconstruct intermediate surfaces using a modified level-set equation, directly linking our NIR with the velocity field. Experiments show that our method significantly outperforms previous NIR approaches across various scenarios (eg, noisy, partial, topology-changing, non-isometric shapes) and, for the first time, enables new applications like 4D Kinect sequence upsampling and real-world high-resolution mesh deformation."
title: "4Deform: Neural Surface Deformation for Robust Shape Interpolation"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
