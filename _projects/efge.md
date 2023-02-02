---
layout: page
title: EFGE
description: Exponential Family Graph Embedding<br>&nbsp;
img: assets/papers/efge.png
importance: -1
category: work
---

##### **Description**
We emphasize on exponential family distributions to capture rich interaction patterns between nodes in random walk sequences. We introduce the generic ***Exponential Family Graph Embedding*** model, that generalizes random walk-based network representation learning techniques to exponential family conditional distributions. We study three particular instances of this model, analyzing their properties and showing their relationship to existing unsupervised learning models. Our experimental evaluation on real-world datasets demonstrates that the proposed techniques outperform well-known baseline methods in two downstream machine learning tasks.

<div class="row row-no-gutters">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/projects/efge/dolphins_2comm_eigen-1.jpg" title="example image" class="img-fluid" %}
        <div style="text-align:center; font-weight:bolder;">Dolphins Network</div>
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/projects/efge/dolphins_method1_dim=2_eigen-1.jpg" title="example image" class="img-fluid" %}
        <div style="text-align:center; font-weight:bolder;">EFGE-Bern</div>
    </div>
</div>
<div class="row row-no-gutters">
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/projects/efge/dolphins_method2_dim=2_eigen-1.jpg" title="example image" class="img-fluid" %}
        <div style="text-align:center; font-weight:bolder;">EFGE-Pois</div>
    </div>
    <div class="col-sm-6 mt-3">
        {% include figure.html path="assets/projects/efge/dolphins_method4_exp_dim=2_eigen-1.jpg" title="example image" class="img-fluid" %}
        <div style="text-align:center; font-weight:bolder;">EFGE-Norm</div>
    </div>
</div>
<div class="caption">
The <i>Dolphins</i> network composed by 2 communities and the corresponding embeddings for d=2.
</div>


##### **Code**
An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/EFGE) repository.

##### **Contributors**
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

---
##### **References**
A. Çelikkanat and F. D. Malliaros, [Exponential Family Graph Embeddings](https://arxiv.org/pdf/1911.09007.pdf), The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI-20), New York City, New York, 2020.


A. Çelikkanat and F. D. Malliaros, [Learning Node Embeddings with Exponential Family Distributions](../../assets/pdf/learning_node_embeddings_with_exponential_family_distributions.pdf), Thirty-third Conference on Neural Information Processing Systems - Workshop on Graph Representation Learning, Vancouver, Canada, 2019