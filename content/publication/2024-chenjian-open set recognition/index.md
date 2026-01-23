---
title: "An Open Set Recognition Method for SAR Targets Combining Unknown Feature Generation and Classification Score Modification"

authors:
  - "Chen Jian"
  - "Yong Qifeng"
  - "Du Lan"
  - "Yin Linwei"

date: "2024-10-11T00:00:00Z"
publishDate: "2024-10-11T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "电子与信息学报"
publication_short: ""
# 替换摘要
abstract: "The existing Synthetic Aperture Radar (SAR) target recognition methods are mostly limited to the closed-set assumption, which considers that the training target categories in training template library cover all the categories to be tested and is not suitable for the open environment with the presence of both known and unknown classes. To solve the problem of SAR target recognition in the case of incomplete target categories in the training template library, an openset SAR target recognition method that combines unknown feature generation with classification score modification is proposed in this paper. Firstly, a prototype network is exploited to get high recognition accuracy of known classes, and then potential unknown features are generated based on prior knowledge to enhance the discrimination of known and unknown classes. After the prototype network being updated, the boundary features of each known class are selected and the distance of each boundary feature to the corresponding class prototype, i.e., maximum distance, is calculated, respectively. Subsequently the maximum distribution area for each known class is determined by the probability fitting of maximum distances for each known class by using extreme value theory. In the testing phase, on the basis of predicting closed-set classification scores by measuring the distance between the testing sample features and each known class prototype, the probability of each distance in the distribution of the corresponding known class’s maximum distance is calculated, and the closed-set classification scores are corrected to automatically determine the rejection probability. Experiments on measured MSTAR dataset show that the proposed method can effectively represent the distribution of unknown class features and enhance the discriminability of known and unknown class features in the feature space, thus achieving accurate recognition for both known class targets and unknown class targets."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://www.jeit.ac.cn/en/article/doi/10.11999/JEIT240138"
# pdf相对路径
url_pdf: "./2024-chenjian-open set recognition.pdf"
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
