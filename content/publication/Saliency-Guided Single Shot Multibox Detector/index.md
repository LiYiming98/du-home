---
title: "Saliency-Guided Single Shot Multibox Detector for Target Detection in SAR Images"

authors:
  - "Lan Du"
  - "Lu Li"
  - "Di Wei"
  - "Jiashun Mao"

date: "2019-12-11T00:00:00Z"
publishDate: "2019-12-11T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Transactions on Geoscience and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "The single shot multibox detector (SSD), a proposal-free method based on convolutional neural network (CNN), has recently been proposed for target detection and has found applications in synthetic aperture radar (SAR) images. Moreover, the saliency information reflected in the saliency map can highlight the target of interest while suppressing clutter, which is beneficial for better scene understanding. Therefore, in this article, we propose a saliency-guided SSD (S-SSD) for target detection in SAR images, in which we effectively integrate the saliency into the SSD network not only to suggest where to focus on but also to improve the representation capability in complex scenes. The proposed S-SSD contains two separated convolutional backbone subnetwork architectures, one with the original SAR image as input to extract features, and the other with the corresponding saliency map obtained from the modified Itti's method as input to acquire refined saliency information under supervision. In addition, the dense connection structure, instead of the plain structure used in original SSD, is applied in the two convolutional backbone architectures to utilize multiscale information with fewer parameters. Then, for integrating saliency information to guide the network to emphasize informative regions, multilevel fusion modules are utilized to merge the two streams into a unified framework, thereby making the whole network end-to-end jointly trained. Finally, the convolutional predictors are used to predict targets. The experimental results on the miniSAR real data demonstrate that the proposed S-SSD can achieve better detection performance than state-of-the-art methods."

summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/8930938"
# pdf相对路径
url_pdf: "./Saliency-Guided Single Shot Multibox Detector.pdf"
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
