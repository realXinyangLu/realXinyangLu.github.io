---
title: "WaterDrum: Watermarking for Data-centric Unlearning Metric"
collection: publications
category: _2026
permalink: /publication/2026-WaterDrum
authors: '<b>Xinyang Lu*</b>, Xinyuan Niu*, Gregory Kang Ruey Lau*, Bui Thi Cam Nhung, Rachael Hwee Ling Sim, Fanyu Wen, Chuan-Sheng Foo, See-Kiong Ng, Bryan Kian Hsiang Low'
venue: "ICLR, 2026"
teaser: "/images/teasers/waterdrum.png"
paperurl: 'https://arxiv.org/abs/2505.05064'
bibtexurl: 'https://academicpages.github.io/files/waterdrum.bib'

---
Large language model (LLM) unlearning is critical in real-world applications where it is necessary to efficiently remove the influence of private, copyrighted, or harmful data from some users. However, existing utility-centric unlearning metrics (based on model utility) may fail to accurately evaluate the extent of unlearning in realistic settings such as when (a) the forget and retain set have semantically similar content, (b) retraining the model from scratch on the retain set is impractical, and/or (c) the model owner can improve the unlearning metric without directly performing unlearning on the LLM. This paper presents the first data-centric unlearning metric for LLMs called WaterDrum that exploits robust text watermarking for overcoming these limitations. We also introduce new benchmark datasets for LLM unlearning that contain varying levels of similar data points and can be used to rigorously evaluate unlearning algorithms using WaterDrum. 
