---
title: "Semi-Supervised SAR ATR Based on Contrastive Learning and Complementary Label Learning"

authors:
  - "Chen Li"
  - "Lan Du"
  - "Yuang Du"

date: "2024-09-25T00:00:00Z"
publishDate: "2024-09-25T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Geoscience and Remote Sensing Letters"
publication_short: ""
# 替换摘要
abstract: "Deep-learning-based methods have recently achieved significant advancements in synthetic aperture radar automatic target recognition (SAR ATR). However, these methods typically rely heavily on extensive annotations, which are difficult to obtain for SAR images. Semi-supervised learning offers a solution to improve model performance with limited labeled data by leveraging unlabeled data. The mainstream semi-supervised learning methods for SAR ATR typically select high-confidence unlabeled images to assign pseudo-labels for their inclusion in the model training process. However, the large number of low-confidence unlabeled images are not efficiently utilized. To address this issue, a semi-supervised SAR target recognition method based on contrastive learning and complementary label (CoL) learning is proposed. First, CoL learning assigns CoLto low-confidence unlabeled images based on their minimum prediction probabilities. Subsequently, a threshold is set to filter out unreliable CoL, thereby mitigating the adverse effects of erroneous CoL. This approach ensures the effective and comprehensive utilization of low-confidence unlabeled images. Additionally, we propose a contrastive loss that incorporates CoL. Compared to traditional contrastive losses, our proposed contrastive loss constructs a richer set of negative sample pairs by leveraging the characteristics of CoL more effectively. Consequently, this approach improves the utilization of low-confidence images and further improves recognition performance. In contrast to the current state-of-the-art semi-supervised recognition methods, experiments on the MSTAR dataset demonstrate the better recognition performance of our proposed method with limited labeled images."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/10693680"
# pdf相对路径
url_pdf: "./2024-lichen-CLCLL.pdf"
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
