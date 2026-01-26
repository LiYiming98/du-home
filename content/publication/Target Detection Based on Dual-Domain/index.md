---
title: "Target Detection Based on Dual-Domain Sparse Reconstruction Saliency in SAR Images"

authors:
  - "Lu Li"
  - "Lan Du"
  - "Zhaocheng Wang"



date: "2018-10-19T00:00:00Z"
publishDate: "2018-10-19T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing"
publication_short: ""
# 替换摘要
abstract: "The conventional target detection methods in synthetic aperture radar (SAR) images usually utilize the clutter information via the clutter statistical modeling. However, it is difficult to select an appropriate clutter statistical distribution model for a real SAR image. To make full use of the clutter information while avoid the clutter statistical modeling, in this paper, we propose a novel target detection method based on the dual-domain sparse reconstruction saliency in SAR images. Considering the speckle noise in SAR images, we utilize not only the intensity information in image domain but also the structure information in feature domain. First, the image-domain saliency map is constructed via the sparse reconstruction on clutter templates extracted from pure clutter SAR images in the image domain with the pixel-level intensity information as the descriptor, and the potential target templates are obtained from this saliency map. Then, the feature-domain saliency map is constructed via the sparse reconstruction on both clutter and potential target templates in the feature domain with the superpixel-level locality-constrained linear coding (LLC) of pixel-level scale invariant feature transform features as the descriptor, where the LLC can describe the spatial and structural information in superpixel level. Finally, the aforementioned two saliency maps are integrated to make our method more robust to speckle noise, and then, the winner-take-all approach is applied to detect targets from the integrated saliency map. We evaluate the proposed method on the miniSAR data and the RADARSAT-2 data. On the miniSAR data, the proposed method is at least 5% higher in terms of AUC than the other saliency methods (i.e., the Itti's method, the SR method, the SVD method, and the JDSR method), and at least 20% higher in F1-score, 22% higher in figure of merit than the Gaussian constant false alarm rate (CFAR), the Gamma-CFAR, and the aforementioned saliency methods. On the RADARSAT-2 data, the proposed method also achieves better performance than the previously compared methods."

summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/8500298"
# pdf相对路径
url_pdf: "./Target Detection Based on Dual-Domain.pdf"
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
