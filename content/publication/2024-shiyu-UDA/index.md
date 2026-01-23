---
title: "Unsupervised Domain Adaptative SAR Target Detection Based on Feature Decomposition and Uncertainty-Guided Self-Training"

authors:
  - "Yu Shi"
  - "Yi Li"
  - "Lan Du"
  - "Yuchen Guo"

date: "2024-11-11T00:00:00Z"
publishDate: "2024-11-11T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "This article proposes an unsupervised domain adaptation (UDA) method by transferring knowledge from rich labeled optical domain to unlabeled synthetic aperture radar (SAR) domain, tackling the issue that current deep-learning-based SAR target detection methods rely on abundant labeled SAR images. Specifically, we gradually encode the dependencies across different granularity perspectives including domain invariant representations (DIR) learning based on feature decomposition and domain discriminative representations (DDR) learning based on uncertainty-guided self-training. First, existing methods usually learn the DIR by directly minimizing domain discrepancy between two domains, which is difficult to achieve in practice. Due to the huge difference between the optical and SAR images, rich domain-specific characteristics bring great challenges to learn the DIR. To alleviate the above difficulty, we explicitly model the domain-invariant and domain-specific features in the representations by constructing a network with feature decomposition to better extract the DIR across domains, where only the DIR extracted from optical images and their labels are used to train the domain-shared detector in this stage. Second, even DIR can be extracted, the domain-shared detector will lose some discriminative and valuable features of the SAR domain while minimizing the distribution discrepancy between the SAR and labeled optical domain. In order to achieve the better detection performance for SAR images, a self-training method based on pseudolabels is proposed to learn DDR and train the SAR-dedicated detector. Furthermore, for ensuring the reliability of pseudolabels, we present a novel uncertainty-guided pseudolabel selection strategy, which contains two phases: one is instance uncertainty guided selection, the other is image uncertainty guided selection. Finally, based on measured optical and SAR datasets, we conduct extensive empirical evaluation to verify the effectuality of our proposed method."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/10750353"
# pdf相对路径
url_pdf: "./2024-shiyu-UDA.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
