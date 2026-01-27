---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Unsupervised Domain Adaptation for SAR Target Detection

# 作者信息
authors:
  - Yu Shi
  - Lan Du
  - Yuchen Guo



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-06-14T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'Recent years have witnessed great progress in synthetic aperture radar (SAR) target detection methods based on deep learning. However, these methods generally assume the training data and test data obey the same distribution, which does not always hold when the radar parameters, imaging algorithm, viewpoints, scenes, etc., change in practice. When such a distribution mismatch occurs, it will cause a significant performance drop. Domain adaptation methods provide an effective way to address this problem by transferring knowledge from the source domain (training data) to the target domain (test data). In this article, we proposed an unsupervised faster R-CNN SAR target detection framework based on domain adaptation, which can improve SAR target detection performance in the unlabeled target domain by borrowing the knowledge of the labeled source domain. Our approach is composed of the following three stages: pixel-domain adaptation (PDA), multilevel feature domain adaptation (MFDA), and iterative pseudolabeling (IPL). By generating transition domain using generative adversarial networks, the PDA stage can reduce the appearance differences of SAR images. At the MFDA stage, the detector can not only learn the domain-invariant global features and instance-level regional features via multilevel adversarial learning in the common feature space but also reweight the low-level global features according to their relative importance to the target domain. At the IPL stage, we design an iterative pseudo labeling strategy that can select pseudo-labels on instance level and image level to encourage the detector to learn more discriminative features of the target domain directly. We evaluate our method using miniSAR and FARADSAR datasets. The experimental results demonstrate the effectiveness of the proposed unsupervised domain adaptation target detection approach.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9454400
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-shiyu-unsupervised domain adaptation for.pdf'
# 都留空
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


image:
  caption: 
  focal_point: ''
  preview_only: false

projects: []
slides:
---
