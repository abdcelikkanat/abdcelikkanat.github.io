---
layout: page
title: PiVeM
description: Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations
img: assets/project_previews/piecewise_velocity_model_for_learning_continuous_time_dynamic_node_representations.gif
importance: -5
category: work
related_publications: false
---

## Description
We propose the **Piecewise-Velocity Model (PiVeM)** for the representation of continuous-time dynamic networks. It learns dynamic embeddings in which the temporal evolution of nodes is approximated by piecewise linear interpolations based on a latent distance model with piecewise constant node-specific velocities. We show that **PiVeM** can successfully represent network structure and dynamics in ultra-low two and three-dimensional embedding spaces. We further extensively evaluate the performance of the approach on various networks of different types and sizes and find that it outperforms existing relevant state-of-art methods in downstream tasks such as link prediction. In summary, **PiVeM** enables easily interpretable dynamic network visualizations and characterizations that can further improve our understanding of the intrinsic dynamics of time-evolving networks.

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%;" controls>
        <source src="/assets/projects/piecewise_velocity_model_for_learning_continuous_time_dynamic_node_representations/synthetic_pi_ground_truth.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div class="caption"><b>Ground Truth</b></div>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%" controls>
        <source src="/assets/projects/piecewise_velocity_model_for_learning_continuous_time_dynamic_node_representations/synthetic_pi_learned_model.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div class="caption"><b>Learned Model</b></div>
    </div>
</div>
<div class="caption">
Comparisons of the ground truth and learned representations in two-dimensional space for the Synthetic(π) dataset.
</div>

## Code
An implementation of the project in Python can be reached at the [Github](https://github.com/abdcelikkanat/pivem) repository.

## Contributors
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Nikolaos Nakis](https://github.com/Nicknakis) and [Morten Mørup](http://www.mortenmorup.dk/)

---
## References
A. Çelikkanat, N. Nakis and M. Mørup, [Piecewise-Velocity Model for Learning Continuous-time Dynamic Node Representations](https://proceedings.mlr.press/v198/celikkanat22a.html), Proceedings of the First Learning on Graphs Conference (LoG 2022), PMLR 198:36:1-36:21, December 9–12, 2022.