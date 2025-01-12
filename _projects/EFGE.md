---
layout: page
title: EFGE
description: Exponential Family Graph Embeddings
img: assets/project_previews/exponential_family_graph_embeddings.png
importance: -2
category: work
related_publications: false
---

## Description
We emphasize on exponential family distributions to capture rich interaction patterns between nodes in random walk sequences. We introduce the generic ***Exponential Family Graph Embedding*** model, that generalizes random walk-based network representation learning techniques to exponential family conditional distributions. We study three particular instances of this model, analyzing their properties and showing their relationship to existing unsupervised learning models. Our experimental evaluation on real-world datasets demonstrates that the proposed techniques outperform well-known baseline methods in two downstream machine learning tasks.

<div class="row">
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/exponential_family_graph_mbeddings/dolphins_2comm_eigen-1.jpg" title="Dolphins Network" class="img-fluid z-depth-0" %}
        <div class="caption"><b>Dolphins Network</b></div>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/exponential_family_graph_mbeddings/dolphins_method1_dim=2_eigen-1.jpg" title="EFGE-Bern" class="img-fluid z-depth-0" %}
        <div class="caption"><b>EFGE-Bern</b></div>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/exponential_family_graph_mbeddings/dolphins_method2_dim=2_eigen-1.jpg" title="EFGE-Pois" class="img-fluid z-depth-0" %}
        <div class="caption"><b>EFGE-Pois</b></div>
    </div>
    <div class="col-sm mt-4 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/projects/exponential_family_graph_mbeddings/dolphins_method4_exp_dim=2_eigen-1.jpg" title="EFGE-Norm" class="img-fluid z-depth-0" %}
        <div class="caption"><b>EFGE-Norm</b></div>
    </div>
</div>
<div class="caption">
The <i>Dolphins</i> network composed by 2 communities and the corresponding embeddings for d=2.
</div>


## Code
An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/EFGE) repository.

## Contributors
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

---
## References
A. Çelikkanat and F. D. Malliaros, [Exponential Family Graph Embeddings](https://arxiv.org/pdf/1911.09007.pdf), The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI-20), New York City, New York, 2020.

A. Çelikkanat and F. D. Malliaros, [Learning Node Embeddings with Exponential Family Distributions](/assets/pdf/learning_node_embeddings_with_exponential_family_distributions.pdf), Thirty-third Conference on Neural Information Processing Systems - Workshop on Graph Representation Learning, Vancouver, Canada, 2019