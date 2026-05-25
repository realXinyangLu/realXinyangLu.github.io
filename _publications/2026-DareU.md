---
title: "De-attribute to Forget for LLM Unlearning"
collection: publications
category: _2026
permalink: /publication/2026-DareU
authors: '<b>Xinyang Lu*</b>, Jiabao Pan*, Rachael Hwee Ling Sim, See-Kiong Ng, Anthony Kum Hoe Tung, Bryan Kian Hsiang Low'
venue: "ICML, 2026"
teaser: "/images/teasers/dareu.png"
paperurl: 'https://arxiv.org/abs/2505.05064'
bibtexurl: 'https://academicpages.github.io/files/dareu.bib'

---
The rapid development of large language models (LLMs) has raised concerns regarding the inclusion of private or inappropriate data during training, which has led to growing interest in LLM unlearning. Many existing LLM unlearning approaches rely on prediction loss-based optimizations, such as maximizing the loss on the forget set. However, these methods often face issues such as over-forgetting and poor model utility. In this work, we address these issues by introducing a novel perspective that shifts the unlearning optimization target to reducing data attribution instead. We propose the first LLM unlearning framework based on data attribution rewards called DareU that employs reinforcement learning to update the LLM and reduce the attribution score of generated responses (i.e., de-attribute) to the forget data owners. Experimental results using an LLM classifier as an efficient approximation of attribution demonstrate that DareU outperforms existing baseline approaches, achieving effective unlearning while balancing forget quality and model utility.
