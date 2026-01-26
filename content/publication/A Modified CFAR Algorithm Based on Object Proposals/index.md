---
title: "A Modified CFAR Algorithm Based on Object Proposals for Ship Target Detection in SAR Images"

authors:
  - "Hui Dai"
  - "Lan Du"
  - "Yan Wang"
  - "Zhaocheng Wang"

date: "2016-11-07T00:00:00Z"
publishDate: "2016-11-07T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Geoscience and Remote Sensing Letters"
publication_short: ""
# 替换摘要
abstract: "Target detection for synthetic aperture radar (SAR) images has great influence on the successive discrimination based on the target regions. However, as a pixel-based method, the traditional constant false alarm rate (CFAR) detection could not work well for the ship target detection problem of multiple ship targets with different sizes in a SAR image, which is referred to as the multiscale situation. Moreover, it needs to use the clustering method on the pixel-level detection results to obtain the accurate target regions, which may merge two or more different targets into a target region. In this letter, a modified CFAR based on object proposals is proposed. We use the object proposal generator to generate a small set of object proposals with different sizes, and then use the proposal-based CFAR detector, where the extracted object proposals are regarded as the guard windows instead of setting fixed guard window, to detect the true positive object proposals. By introducing the object proposals as the variable guard windows in the CFAR detector, the proposed algorithm could gain good detection performance in the multiscale situation, since the missed detection resulting from the big differences between the sizes of the fixed guard window and ship targets can be avoided. Meanwhile, the proposed method can directly obtain the accurate target regions. The effectiveness of the proposed algorithm is verified using the measured SAR data."

summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/7737020"
# pdf相对路径
url_pdf: "./A Modified CFAR Algorithm Based on Object Proposals.pdf"
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
