---
layout: page
title: TNE
description: Topic-aware latent models for representation learning on networks
img: assets/papers/tne_journal.png
importance: -1
category: work
---

##### **Description**
We introduce **TNE**, a generic framework to enhance the embeddings of nodes acquired by means of random walk-based approaches with topic-based information. Similar to the concept of topical word embeddings in Natural Language Processing, the proposed model first assigns each node to a latent community  with the favor of various statistical graph models and community detection methods, and then learns the enhanced topic-aware representations. We evaluate our methodology in two downstream tasks: node classification and link prediction. The experimental results demonstrate that by incorporating node and community embeddings, we are able to outperform widely-known baseline NRL models.


<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/projects/tne/tne_overview.png" title="tne" class="img-fluid rounded" %}
    </div>
</div>

##### **Code**
The implementation of the *TNE* framework in Python can be reached at the [Github](https://github.com/abdcelikkanat/TNE) repository.

##### **Contributors**
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

---
##### **References**
A. Celikkanat and F. D. Malliaros, [TNE: A Latent Model for Representation Learning on Networks](/assets/pdf/TNE_NeurIPS_R2L_2018.pdf), NeurIPS Relational Representation Learning Workshop (NeurIPS-R2L), *Montréal*, *Canada*, 2018

A. Celikkanat and F. D. Malliaros, [Topic-aware latent models for representation learning on networks](https://doi.org/10.1016/j.patrec.2021.01.006), Pattern Recognition Letters, 2021