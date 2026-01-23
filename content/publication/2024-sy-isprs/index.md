---
title: "Unsupervised domain adaptation for SAR target classification based on domain-and class-level alignment: From simulated to real data"

authors:
  - "Yu Shi"
  - "Lan Du"
  - "Chen Li"
  - "Yuchen Guo"
  - "Yuang Du"

date: "2024-01-01T00:00:00Z"
publishDate: "2024-01-01T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "ISPRS Journal of Photogrammetry and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "Synthetic Aperture Radar (SAR) target classification methods based on convolutional neural networks have attracted wide attention recently. Typically, these methods necessitate a substantial quantity of labeled data to train the deep model, which is an obstacle for SAR target classification since annotating SAR images is costly and time-consuming. Generating large-scale labeled data in simulation to train the deep model is a feasible alternative. However, cross-domain recognition is challenging due to significant differences in distribution between simulated and real domains. In this paper, we propose an unsupervised domain adaptation method for SAR target classification by aligning the distribution between the simulated and unlabeled real domains. Specifically, we encode the dependencies across different granularity perspectives including domain-, and class-levels simultaneously to align two domains finely. On the one hand, a gradient-weighted adversarial alignment method is proposed to align the global distributions at the domain-level. On the other hand, a novel class-level alignment method based on the prototypical network is proposed to align the finer class structure. Technically, we respectively model the cross-domain prototype-prototype relations and cross-domain prototype-instance relations with contrastive learning to achieve intra-class prototype compact as well as inter-class prototype separation among cross-domain categories, where the prototypes of the real domain are learned with pseudo labels. To improve the quality of pseudo-labels, a pseudo-label filtering strategy combined with the attribute scattering center is further designed. The experiments on two simulation-to-reality datasets indicate that the proposed method outperforms state-of-the-art unsupervised domain adaptive methods, such as pixelfeat (+4.45% and +7.6% in accuracy on SAMPLE and S2M datasets respectively). Code and data will be available in https://github.com/YuShi1213/Sim2Real-Unsupervised-SAR-Target-Classification."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://www.sciencedirect.com/science/article/pii/S0924271623003155"
# pdf相对路径
url_pdf: "./2024-sy-isprs.pdf"
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
