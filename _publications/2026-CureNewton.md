---
title: "Batch and Sequential Unlearning for Neural Networks"
collection: publications
category: _2026
permalink: /publication/2026-CureNewton
authors: 'Nhung Bui*, </b>Xinyang Lu*</b>, Rachael Hwee Ling Sim, See-Kiong Ng, Bryan Kian Hsiang Low'
venue: "ICLR, 2026"
teaser: "/images/teasers/newton.png"
paperurl: 'https://arxiv.org/abs/2406.14507'
bibtexurl: 'https://academicpages.github.io/files/curenewton.bib'
---

With the increasing deployment of machine learning models trained on personal data, machine unlearning has become crucial for data owners to exercise their "right to be forgotten" and protect their privacy. While model owners can retrain the models without the erased data to achieve this goal, this process is often prohibitively expensive. Previous works have shown that Newton's method can be applied to linear models to unlearn multiple data points in batch (batch unlearning) with minimal iterations. However, adapting this method to non-linear models, such as neural networks, poses significant challenges due to the presence of degenerate Hessians. This problem becomes more pronounced when unlearning is performed sequentially (sequential unlearning). Existing techniques that tried to tackle this degeneracy often 1) incur unlearning updates with excessively large norm that yield unsatisfactory unlearning performance and 2) may require manual tuning of regularization hyperparameters. In this work, we propose new unlearning algorithms that leverage cubic regularization for Newton's method to address both challenges. We discuss the theoretical benefits of our method and empirically show that our algorithms can efficiently achieve competitive performance in both batch and sequential unlearning on real-world datasets.
