---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: A Novel SAR Target Recognition Method Combining Electromagnetic Scattering Information and GCN

# 作者信息
authors:
  - Chen Li
  - Lan Du
  - Yi Li
  - Jialun Song



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-06-01T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Geoscience and Remote Sensing Letters'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'The existing deep learning studies on synthetic aperture radar (SAR) automatic target recognition (ATR) mainly focus on the utilization of the amplitude of SAR image via convolutional neural network (CNN), while the electromagnetic scattering information is rarely considered. Given that scattering centers (SCs) can characterize the target’s electromagnetic scattering characteristics and describe the target’s physical structure information, the SC feature should be helpful for SAR ATR. Therefore, we propose a novel SAR ATR method that combines electromagnetic scattering information and graph convolutional network (GCN) effectively and directly. Specifically, we model each extracted SC as a node to convert the SCs into graph data. The constructed graph is learned via GCN to describe the target’s physical structure information, where the features of different GCN layers are fused to avoid the oversmoothing of GCN. Label smoothing is combined with GCN for the first time to alleviate the overfitting caused by the limited training data. To the best of our knowledge, this study is the first to introduce the GCN for effectively utilizing the SCs, proving that the structural characteristics of the SCs of SAR targets are remarkably beneficial for recognition. Extensive experimental results on the measured moving and stationary target acquisition and recognition (MSTAR) dataset show that our method can obtain superior recognition performance compared with the existing methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9786635
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-lichen-a novel SAR target.pdf'
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
