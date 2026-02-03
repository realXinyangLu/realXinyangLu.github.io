---
title: "Global-to-Local Support Spectrums for Language Model Explainability"
collection: publications
category: _2024
permalink: /publication/2024-global
authors: 'Lucas Agussurja, <b>Xinyang Lu</b>, Bryan Kian Hsiang Low'
venue: "Preprint, 2024"
teaser: "/images/teasers/global.png"
paperurl: 'https://arxiv.org/abs/2408.05976'
bibtexurl: 'https://academicpages.github.io/files/global.bib'
---

Existing sample-based methods, like influence functions and representer points, measure the importance of a training point by approximating the effect of its removal from training. As such, they are skewed towards outliers and points that are very close to the decision boundaries. The explanations provided by these methods are often static and not specific enough for different test points. In this paper, we propose a method to generate an explanation in the form of support spectrums which are based on two main ideas: the support sets and a global-to-local importance measure. The support set is the set of training points, in the predicted class, that ``lie in between'' the test point and training points in the other classes. They indicate how well the test point can be distinguished from the points not in the predicted class. The global-to-local importance measure is obtained by decoupling existing methods into the global and local components which are then used to select the points in the support set. Using this method, we are able to generate explanations that are tailored to specific test points. In the experiments, we show the effectiveness of the method in image classification and text generation tasks.
