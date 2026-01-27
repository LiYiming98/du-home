---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: A Novel Method Combining Global Visual Features and Local Structural Features for SAR ATR

# 作者信息
authors:
  - Chen Li
  - Lan Du
  - Yi Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2023-10-13T00:00:00Z'

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
abstract: 'The mainstream synthetic aperture radar (SAR) automatic target recognition (ATR) methods commonly use convolutional neural network (CNN) to extract the visual information of SAR targets, while the physical structural information is seldom considered. Scattering center features can describe the targets’ physical structure information and are robust to the local variations of targets, which can be exploited to reflect the local structural characteristic of SAR targets. Therefore, we propose a novel method that effectively combines global visual features and local structural features for SAR ATR. The local structural features here contain not only the local physical structure information but also the local visual information. Our proposed method consists of three parts: global-based module, local-based module, and feature fusion module. Global-based module utilizes CNN to extract global visual features from SAR images. Local-based module first extracts attributed scattering centers (ASCs) from the complex SAR image and models each ASC as a node to construct graph data, from which we further use a multiscale graph convolutional network (GCN) to extract local structural features. The node features for GCN learning are constructed by multiplying the corresponding local visual features in shallow CNN feature maps with the ASC reconstruction maps to better reflect the local structure characteristic. Then, the learned local structural features from GCN are further fused with global visual features to achieve SAR ATR. As far as authors know, this is the first work combining CNN and GCN to effectively extract global visual features and local structural features simultaneously in SAR ATR. Experiments on the moving and stationary target acquisition and recognition (MSTAR) dataset show that our proposed method outperforms SOTA methods in terms of classification accuracy.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/10285480
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2023-lichen-a novel method combining.pdf'
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
