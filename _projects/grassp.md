---
layout: page
title: GraSSP
description: GraSSP - Continuous-time Graph Representation with Sequential Survival Process
img: assets/project_previews/grassp_continuous-time_graph_representation_with_sequential_survival_process.gif
importance: -6
category: work
related_publications: false
---

## Description
Over the past two decades, there has been a tremendous increase in the growth of representation learning methods for graphs, with numerous applications across various fields, including bioinformatics, chemistry, and the social sciences. However, current dynamic network approaches focus on discrete-time networks or treat links in continuous-time networks as instantaneous events. Therefore, these approaches have limitations in capturing the persistence or absence of links that continuously emerge and disappear over time for particular durations. 

<div class="row">
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%;" controls>
        <source src="/assets/projects/grassp_continuous_time_graph_representation_with_sequential_survival_process/synthetic_n=100_seed=16.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div class="caption"><b>Ground Truth</b></div>
    </div>
    <div class="col-sm mt-5 mt-md-0">
        <video width="100%" controls>
        <source src="/assets/projects/grassp_continuous_time_graph_representation_with_sequential_survival_process/synthetic_n=100_seed=16_B=100_lambda=1e8_dim=2_epoch=300_spe=10_bs=100_lr=0.1_seed=10_anim_edge_alpha=0.15.mp4" type="video/mp4">
        Your browser does not support the video tag.
        </video>
        <div class="caption"><b>Learned Model</b></div>
    </div>
</div>
<div class="caption">
Comparisons of the ground truth and learned representations in two-dimensional space for the Synthetic(π) dataset.
</div>

To address this, we propose a novel stochastic process relying on survival functions to model the durations of links and their absences over time. This forms a generic new likelihood specification explicitly accounting for intermittent edge-persistent networks, namely GraSSP: Graph Representation with Sequential Survival Process. We apply the developed framework to a recent continuous time dynamic latent distance model characterizing network dynamics in terms of a sequence of piecewise linear movements of nodes in latent space. We quantitatively assess the developed framework in various downstream tasks, such as link prediction and network completion, demonstrating that the developed modeling framework accounting for link persistence and absence well tracks the intrinsic trajectories of nodes in a latent space and captures the underlying characteristics of evolving network structure.


### Code
An implementation of the project in Python can be reached at the [Github](https://github.com/abdcelikkanat/grassp) repository.

## Contributors
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Nikolaos Nakis](https://github.com/Nicknakis) and [Morten Mørup](http://www.mortenmorup.dk/)

---
## References
A. Çelikkanat, N. Nakis and M. Mørup, [Continuous-time Graph Representation with Sequential Survival Process](https://ojs.aaai.org/index.php/AAAI/article/view/28995), Proceedings of the AAAI Conference on Artificial Intelligence. 2024.