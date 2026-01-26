---
title: "SAR Target Detection Based on SSD With Data Augmentation and Transfer Learning"

authors:
  - "Zhaocheng Wang"
  - "Lan Du"
  - "Jiashun Mao"
  - "Bin Liu"
  - "Dongwen Yang"

date: "2018-09-18T00:00:00Z"
publishDate: "2018-09-18T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "IEEE Geoscience and Remote Sensing Letters"
publication_short: ""
# 替换摘要
abstract: "In this letter, the single shot multibox detector (SSD), which is a real-time object detection method based on convolutional neural network, is applied to realize target detection for synthetic aperture radar (SAR) images. Since there are no sufficient labeled images for training in SAR target detection, we apply two strategies, data augmentation and transfer learning. For data augmentation, the first approaches to use some image processing methods, i.e., manual-extracting subimages, adding noise, filtering, and flipping, on the original training images to generate some new training images; the second approach is to employ the existing SAR target recognition data set, MSTAR data set, to assist in accomplishing the target detection task. For transfer learning, we first apply subaperture decomposition technique on original SAR images to acquire three-channel subaperture SAR images, and then transfer the three-channel VGGNet model pretrained on the ImageNet data set to the three-channel subaperture SAR images, in order to initialize corresponding parameters of the convolutional layers in the base network in our SSD. The feature extraction network, consisting of the base network and the auxiliary structure, is used to learn multiscale feature maps, and then convolutional predictors are used to acquire the final detection results. The experimental results on the miniSAR real image data set demonstrate that the proposed method can obtain better detection performance than other detection methods."

summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://ieeexplore.ieee.org/abstract/document/8467523"
# pdf相对路径
url_pdf: "./SAR Target Detection Based on SSD.pdf"
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
