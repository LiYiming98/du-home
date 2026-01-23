---
title: "An Open Set Recognition for SAR Targets Based on Encoding-Conditional Decoding Network with Reject Threshold Adaptation"

authors:
  - "Yiming Li"
  - "Lan Du"
  - "Jian Chen"
  - "Jialun Song"
  - "Zilin Wang"
  - "Yuchen Guo"

date: "2024-06-18T00:00:00Z"
publishDate: "2024-06-18T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "Current synthetic aperture radar (SAR) automatic target recognition (ATR) methods primarily focus on closed set recognition, i.e., they typically assume that the training set covers all target classes that appear in the test set. However, this assumption may not hold in practical scenarios, where it's inevitable to encounter high-value targets whose classes are absent from the training set. In this article, we propose an open set recognition (OSR) based on the encoding-conditional decoding network with reject threshold adaptation (ECTA) for SAR targets. The ECTA consists of four parts: 1) the encoding; 2) classification; 3) conditional decoding; and 4) reject threshold calculation modules. The encoding module learns the latent representation of the training samples, which is then fed to the classification part to predict the class labels. The conditional decoding module is trained to produce matching reconstructed samples by combining the latent representation with the label corresponding to the target class while producing nonmatching reconstructed samples by combining the latent representation with the label corresponding to a random other target class. Through the proposed reconstruction strategy, the conditional decoding module gives an approximate description of the known and unknown class reconstruction error distributions, building the foundation for the reject threshold calculation module. The reject threshold calculation module fits the extreme value distributions of matching and nonmatching reconstruction errors based on extreme value theory (EVT) and finally obtains satisfactory reject thresholds adaptively by minimizing the probability of false positives and false negatives. Experiments conducted on two measured datasets indicate that ECTA outperforms state-of-the-art OSR methods."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/10562242"
# pdf相对路径
url_pdf: "./2024-lym-osr.pdf"
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
