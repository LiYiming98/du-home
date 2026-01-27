---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Cross Sensor Transfer Learning for Unsupervised SAR Target Detection

# 作者信息
authors:
  - Yu Shi
  - Lan Du
  - Yuchen Guo
  - Jian Chen



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2023-02-08T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '2021 CIE International Conference on Radar (Radar)'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'Synthetic Aperture Radar (SAR) target detection based on deep learning typically assume the training and test data drawn from the same distribution. However, when the radar sensors change, this assumption does not always hold and will cause to a performance degradation when encountering such distribution mismatch. Transfer learning shares a great idea to solve this issue by transferring knowledge from the labeled data of source sensor to the unlabeled data of target sensor. We proposed a cross sensor transfer learning method based on domain adaptation, which can improve the cross sensor robustness of SAR target detection with unlabeled target sensor (domain) data. Our method includes three stages: pixel domain diverse (PDD), multilevel feature alignment (MFA) and iterative self-training (IST). The PDD stage can alleviate the few training data of SAR target detection and enhance the generalization ability by generating transition domain. MFA can learn domain invariant features in a multi-layer feature space by using the idea of adversarial learning. To learn more discriminative features, we further proposed the IST that can generate and select high-quality pseudo labels for the SAR images of target sensor. The experimental results on miniSAR and FARADSAR datasets demonstrate the effectiveness of the proposed approach.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/10028188
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-shiyu-cross sensor transfer learning.pdf'
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
