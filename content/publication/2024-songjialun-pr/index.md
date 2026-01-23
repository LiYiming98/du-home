---
title: "Rebalancing network with knowledge stability for class incremental learning"

authors:
  - "Jialun Song"
  - "Jian Chen"
  - "Lan Du"

date: "2024-09-01T00:00:00Z"
publishDate: "2024-09-01T00:00:00Z"
# 会议1，期刊2
publication_types: ["2"]
# 替换期刊名称
publication: "Pattern Recognition"
publication_short: ""
# 替换摘要
abstract: "Class incremental learning (CIL) has been proposed to solve the problem of learning to classify new classes while maintaining the performance on old classes. A typical strategy is to update the old classification model with entire new class data and a few old exemplars, which face serious performance degradation on old classes. The main reasons come down to class imbalance between old and new classes along with catastrophic forgetting towards old classes. Most existing CIL methods have proposed solving the above two issues in classification space, ignoring their adverse effects of overlapping between old and new classes and confusion among old classes in feature space. In this paper, we propose a rebalancing network with knowledge stability (RNKS), aiming to adequately retain the model performance on old classes in CIL by solving class imbalance and catastrophic forgetting in feature and classification space simultaneously. In detail, the proposed RNKS mainly consists of multi-proxies rebalancing (MPR) and hybrid knowledge distillation (HKD). MPR, focusing on class imbalance, employs multi-proxies metric learning to decrease the feature overlapping between old and new classes, together with balanced data sampling to correct the skewed decision boundary. HKD, coping with catastrophic forgetting, encourages the updated model to reproduce identical feature topologies and predictions of old classes as the old model via feature relation-based and response-based distillations. Experiments on CIFAR-100 and ILSVRC datasets demonstrate the effectiveness of this work against the state-of-the-art approaches."
summary: ""
tags: []
featured: false
# 网页链接
links:
  - name: "Web Link"
    url: "https://www.sciencedirect.com/science/article/pii/S0031320324002577"
# pdf相对路径
url_pdf: "./2024-songjialun-pr.pdf"
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
