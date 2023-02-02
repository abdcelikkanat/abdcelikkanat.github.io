---
layout: page
title: PiVeM
description: Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations
img: assets/papers/pivem.gif
importance: -4
category: work
---

##### **Description**
We propose the **Piecewise-Velocity Model (PiVeM)** for the representation of continuous-time dynamic networks. It learns dynamic embeddings in which the temporal evolution of nodes is approximated by piecewise linear interpolations based on a latent distance model with piecewise constant node-specific velocities. We show that **PiVeM** can successfully represent network structure and dynamics in ultra-low two and three-dimensional embedding spaces. We further extensively evaluate the performance of the approach on various networks of different types and sizes and find that it outperforms existing relevant state-of-art methods in downstream tasks such as link prediction. In summary, **PiVeM** enables easily interpretable dynamic network visualizations and characterizations that can further improve our understanding of the intrinsic dynamics of time-evolving networks.

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%;" controls>
        <source src="../../assets/projects/pivem/synthetic_pi_ground_truth.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div style="text-align:center; font-weight:bolder;">Ground Truth</div>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%" controls>
        <source src="../../assets/projects/pivem/synthetic_pi_learned_model.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div style="text-align:center; font-weight:bolder;">Learned Model</div>
    </div>
</div>
<div class="caption">
Comparisons of the ground truth and learned representations in two-dimensional space for the Synthetic(π) symbol.
</div>

##### **Code**
An implementation of the project in Python can be reached at the [Github](https://github.com/abdcelikkanat/pivem) repository.

##### **Contributors**
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Nikolaos Nakis](https://github.com/Nicknakis) and [Morten Mørup](http://www.mortenmorup.dk/)

---
##### **References**
A. Çelikkanat, N. Nakis and M. Mørup, [Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations](.), Proceedings of the First Learning on Graphs Conference (LoG 2022), PMLR 198:36:1-36:21, December 9–12, 2022.