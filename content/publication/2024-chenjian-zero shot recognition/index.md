---
title: "SAR Target Zero-Shot Recognition with OpticalImage Assistance"

authors:
  - "Jian Chen"
  - "Qifeng Yong"
  - "Lan Du"
  - "Yashi Zhou"
  - "Jie Liu"

date: "2025-02-12T00:00:00Z"
publishDate: "2025-02-12T00:00:00Z"
# 会议1，期刊2
publication_types: ["1"]
# 替换期刊名称
publication: "2024 IEEE International Conference on Signal, Information and Data Processing (ICSIDP)"
publication_short: ""
# 替换摘要
abstract: "Most synthetic aperture radar (SAR) target recognition (ATR) methods focus on closed set conditions, which assumes that the testing set shares the same label space with the training set. However, new targets inevitably appear in practical testing phase. Closed-set SAR target recognition methods will misclassify those unseen new targets as the known targets in training phase, causing decision errors. Zero-shot recognition (ZSR) is an effective way to make predictions for unknown classes. Existing ZSR methods, which are primarily designed for optical images, typically construct an attribute knowledge base shared among known and unknown targets, and then learn the feature-attribute mapping using only known class data, which is subsequently applied to predict attributes of unknowns during testing and achieve class judgment. Unfortunately, the optical ZSR methods do not perform well in SAR data, due to the huge difficulty in the learning of feature-attribute mapping caused by the less accurate target representation of SAR images than the optical images. To overcome this problem, this paper proposes a ZSR method of SAR target with optical image assistance. In detail, on the basis of attribute knowledge base construction, the proposed method maps the known optical and SAR training data to the feature space through their respective feature extraction network, and uses feature aggregation loss to ensure that optical and SAR image features from the same category are close to each other, while those from different categories remain far apart. Based on the alignment of optical and SAR features, the feature-attribute mapping is learned using both SAR and optical data, leveraging the advantages of optical images in the easier and more accurate learning of feature-attribute mapping to promote the learning of SAR images. In testing phase, the learned SAR feature extraction network and feature-attribute mapping are used to predict unknown targets’ attributes. Ultimately, the unknown class prediction is realized by measuring the similarities between the predicted attributes and true attributes from all unknown targets which can be obtained according to the prior knowledge. Experiments on measured ship dataset demonstrate that our method achieves superior recognition performance compared to existing ZSR methods using only SAR data."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/10868138"
# pdf相对路径
url_pdf: "./2024-chenjian-zero shot recognition.pdf"
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
