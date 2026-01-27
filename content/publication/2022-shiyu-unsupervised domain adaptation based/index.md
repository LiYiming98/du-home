---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Unsupervised Domain Adaptation Based on Progressive Transfer for Ship Detection:From Optical to SAR Images

# 作者信息
authors:
  - Shi Yu
  - Lan Du
  - Yuchen Guo
  - Yuang Du



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-06-22T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Geoscience and Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'In recent years, synthetic aperture radar (SAR) ship detection methods based on convolutional neural networks (CNNs) have attracted wide attention in remote sensing fields. However, these methods require a large number of labeled SAR images to train the network, where labeling for SAR images is more expensive and time-consuming than that for optical images. To address the problem of lacking labeled SAR images, in this article, we proposed an unsupervised domain adaptation (UDA) framework based on progressive transfer for SAR ship detection by transferring knowledge from the optical domain to the SAR domain. Due to the prominent difference between the optical and SAR images, our approach progressively transfers knowledge from three levels: pixel level, feature level, and prediction level. At the pixel level, considering the difference in imaging mechanism, we propose a special data augmentation method for ship targets and build the generator with skip connection based on generative adversarial networks (GANs) to generate transition domain, which can reduce the appearance discrepancy between the optical and SAR images. At the feature level, the detector is trained to learn the domain-invariant features with adversarial alignment. At the prediction level, we further use the predicted pseudo-labels obtained by the feature-aligned detector to learn more discriminative features of the SAR images directly and propose the robust self-training (RST) method to reduce the influence of noisy pseudo-labels on detector training. Specially, RST is formulated as a loss minimization problem for object detection. The experimental results based on the domain adaptation from optical dataset to SAR dataset demonstrate that our approach achieves superior SAR ship detection performance with unlabeled SAR images.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9803220
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-shiyu-unsupervised domain adaptation based.pdf'
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
