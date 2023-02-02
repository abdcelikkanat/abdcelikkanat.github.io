---
layout: page
title: NodeSig
description: NodeSig&#58; Binary Node Embeddings via Random Walk Diffusion
img: assets/papers/nodesig.png
importance: -3
category: work
---

##### **Description**
As the scale of networks increases, most of the widely used learning-based graph representation models also face computational challenges. While there is a recent effort toward designing algorithms that solely deal with scalability issues, most of them behave poorly in terms of accuracy on downstream tasks. In this paper, we aim to study models that balance the trade-off between efficiency and accuracy. In particular, we propose NodeSig, a  scalable model that computes binary node representations. NodeSig exploits random walk diffusion probabilities via stable random projections towards efficiently computing embeddings in the Hamming space. Our extensive experimental evaluation on various networks has demonstrated that the proposed model achieves a good balance between accuracy and efficiency compared to well-known baseline models on the node classification and link prediction tasks.


<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/projects/nodesig/random_walks.png" title="example image" class="img-fluid rounded" %}
    </div>
</div>

##### **Code**
An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/nodesig) repository.

##### **Contributors**
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Apostolos N. Papadopoulos](http://delab.csd.auth.gr/~apostol/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

---
##### **References**
A. Celikkanat, F. D. Malliaros and  A. N. Papadopoulos, [NodeSig: Binary Node Embeddings via Random Walk Diffusion](.), The 2022 IEEE/ACM International Conference on Advances in Social Network Analysis and Mining (ASONAM-22), Istanbul, Turkey, 2022.
