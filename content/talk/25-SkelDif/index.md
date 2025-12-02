---
author: Cecilia Curreli, Dominik Muhle, Abhishek Saroha, Zhenzhang Ye, **Riccardo Marin**, Daniel Cremers
categories:
- Conference
date: "2025-04-22"
date_end: ""
draft: false
event:  IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2025.
event_url: 
excerpt: We propose a novel diffusion noise scheduler that takes into account the skeleton structure. Instead of assuming that every joint is an independent variable (isotropic), we use the kinematic tree to take into account the joints' interdependencies in the noise formulation (Nonisotropic). We apply this framework to the human motion prediction task, resulting in more diverse and realistic motion than previous works.
featured: false
layout: single
links:
- icon: archive
  icon_pack: fas
  name: Project Page
  url: https://ceveloper.github.io/publications/skeletondiffusion/
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://arxiv.org/abs/2501.06035
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/Ceveloper/SkeletonDiffusion/tree/main
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Probabilistic human motion prediction aims to forecast multiple possible future movements from past observations. While current approaches report high diversity and realism, they often generate motions with undetected limb stretching and jitter. To address this, we introduce SkeletonDiffusion, a latent diffusion model that embeds an explicit inductive bias on the human body within its architecture and training. Our model is trained with a novel nonisotropic Gaussian diffusion formulation that aligns with the natural kinematic structure of the human skeleton. Results show that our approach outperforms conventional isotropic alternatives, consistently generating realistic predictions while avoiding artifacts such as limb distortion. Additionally, we identify a limitation in commonly used diversity metrics, which may inadvertently favor models that produce inconsistent limb lengths within the same sequence. SkeletonDiffusion sets a new benchmark on three real-world datasets, outperforming various baselines across multiple evaluation metrics."
title: "Nonisotropic Gaussian Diffusion for Realistic 3D Human Motion Prediction"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
