---
title: "Unsupervised Domain Adaptation for Ship Classification via Progressive Feature Alignment: From Optical to SAR Images"

authors:
  - "Yu Shi"
  - "Lan Du"
  - "Yuchen Guo"
  - "Yuang Du"
  - "Yiming Li"

date: "2024-09-12T00:00:00Z"
publishDate: "2024-09-12T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Transactions on Geoscience and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "This article delves into the topic of unsupervised domain adaptation (UDA) by transferring knowledge from rich labeled optical domain to unlabeled synthetic aperture radar (SAR) domain, tackling the issues faced by deep-learning-based SAR ship classification methods that rely on abundant labeled SAR images. Typical UDA methods usually extract domain-invariant representations (DIRs) between two domains. However, due to the prominent differences in imaging mechanisms between optical and SAR images, the discriminative characteristics of same classes across domains may vary. Feature representation guided by labeled optical images therefore suffers from a particularly serious source-bias problem, making DIR difficult to be extracted. Moreover, capturing the category structure of the target domain is crucial for classification tasks. To solve the above challenges, this article proposes a UDA framework for SAR ship classification via progressive feature alignment between optical and unlabeled SAR domains, gradually aligning two domains across domain and class levels. At the domain level, to reduce the transfer difficulty stemming from the prominent differences between SAR and optical images, feature calibrated domain alignment (FCDA) is presented to achieve accurate DIR extraction. FCDA combines the reconstruction and the consistency constraints of different perturbed versions of the same image to calibrate the optical-bias representation into the features of unbiased toward a specific domain. At the class level, we proposed feature enhanced class alignment (FECA) to capture the fine-grained category structure of the SAR domain. FECA incorporates pseudo-label-based cross-domain contrastive learning (CDC) for intraclass compactness as well as interclass separation among cross-domain categories, along with a consistency learning approach to enhance the class structure of SAR domain. The experimental results indicate that our method achieves exceptional performance in unsupervised classification of SAR ships."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/10679175"
# pdf相对路径
url_pdf: "./2024-shiyu-tgrs.pdf"
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
