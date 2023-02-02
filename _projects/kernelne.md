---
layout: page
title: MKernelNE
description: Multiple Kernel Representation Learning on Networks<br>&nbsp;
img: assets/papers/mkernelne.png
importance: -2
category: work
---

##### **Description**

Learning representations of nodes in a low dimensional space is a crucial task with numerous interesting applications in network analysis, including link prediction, node classification, and visualization. Two popular approaches for this problem are <i>matrix factorization</i> and <i>random walk</i>-based models. 

<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/projects/mkernelne/mkernelne.jpg" title="example image" class="img-fluid rounded" %}
    </div>
</div>

In this work, we aim to bring together the best of both worlds, towards learning node representations. In particular, we propose a weighted matrix factorization model that encodes random walk-based information about nodes of the network. The benefit of this novel formulation is that it enables us to utilize kernel functions without realizing the exact proximity matrix so that it enhances the expressiveness of existing matrix decomposition methods with kernels and alleviates their computational complexities. We extend the approach with a multiple kernel learning formulation that provides the flexibility of learning the kernel as the linear combination of a dictionary of kernels in data-driven fashion. We perform an empirical evaluation on real-world networks, showing that the proposed model outperforms baseline node embedding algorithms in downstream machine learning tasks.

##### **Code**
An implementation of the project in C++ can be reached at the [Github](https://github.com/abdcelikkanat/kernelNE) repository.

##### **Contributors**
[Abdulkadir Çelikkanat](http://abdcelikkanat.github.io/), [Yanning Shen](https://sites.google.com/uci.edu/yanning-shen/) and [Fragkiskos D. Malliaros](http://fragkiskos.me)

---
##### **References**
A. Celikkanat and F. D. Malliaros, [Kernel Node Embeddings](https://doi.org/10.1109/GlobalSIP45357.2019.8969363), 7th IEEE Global Conference on Signal and Information Processing (GlobalSIP), 2019


A. Celikkanat,  Y. Shen and F. D. Malliaros, [Multiple Kernel Representation Learning on Networks](https://doi.org/10.1109/TKDE.2022.3172048), IEEE Transactions on Knowledge and Data Engineering, 2022
