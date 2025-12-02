---
author: Ilya A Petrov, **Riccardo Marin**, Julian Chibane, Gerard Pons-Moll
categories:
- Conference
date: "2025-05-22"
date_end: ""
draft: false
event:  IEEE/CVF International Conference on Computer Vision (ICCV), 2025.
event_url: 
excerpt: A unified framework for generative 3D Human-Object Interaction, capable of operating in seven different modes.
featured: true
layout: single
links:
- icon: archive
  icon_pack: fas
  name: Project Page
  url: https://virtualhumans.mpi-inf.mpg.de/tridi/
- icon: paper-plane
  icon_pack: fas
  name: article
  url: https://openaccess.thecvf.com/content/ICCV2025/papers/Petrov_TriDi_Trilateral_Diffusion_of_3D_Humans_Objects_and_Interactions_ICCV_2025_paper.pdf
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/ptrvilya/tridi
#- icon: quote-left
#  icon_pack: fas
#  name: cite
#  url: https://github.com/filthynobleman/slime-manifold
location: 
show_post_time: false
bibtex: True
subtitle: "Modeling 3D human-object interaction (HOI) is a problem of great interest for computer vision and a key enabler for virtual and mixed-reality applications. Existing methods work in a one-way direction: some recover plausible human interactions conditioned on a 3D object; others recover the object pose conditioned on a human pose. Instead, we provide the first unified model-TriDi which works in any direction. Concretely, we generate Human, Object, and Interaction modalities simultaneously with a new three-way diffusion process, allowing to model seven distributions with one network. We implement TriDi as a transformer attending to the various modalities' tokens, thereby discovering conditional relations between them. The user can control the interaction either as a text description of HOI or a contact map. We embed these two representations onto a shared latent space, combining the practicality of text descriptions with the expressiveness of contact maps. Using a single network, TriDi unifies all the special cases of prior work and extends to new ones modeling a family of seven distributions. Remarkably, despite using a single model, TriDi generated samples surpass one-way specialized baselines on GRAB and BEHAVE in terms of both qualitative and quantitative metrics, and demonstrating better diversity. We show applicability of TriDi to scene population, generating object for human-contact datasets, and generalization to unseen object geometry."
title: "Tridi: Trilateral diffusion of 3d humans, objects, and interactions"

---
**NOTE**

It works with almost all markdown flavours (the below blank line matters).

---
---

I'm really excited to give this talk! Stay tuned for video and slides.
