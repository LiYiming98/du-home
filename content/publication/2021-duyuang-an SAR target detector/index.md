---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: An SAR Target Detector Based on Gradient Harmonized Mechanism and Attention Mechanism

# 作者信息
authors:
  - Yuang Du
  - Lan Du
  - Lu Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-08-17T00:00:00Z'

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
abstract: 'In this letter, a target detector based on gradient harmonized mechanism (GHM) and attention mechanism is proposed to realize synthetic aperture radar (SAR) target detection in complex scenes. Considering the imbalance of positive and negative examples in SAR target detection, we use RefineDet as our backbone network. RefineDet can mitigate this imbalance problem by introducing the idea of two-step classification and regression into the one-stage detector. However, RefineDet only selects a part of examples for training and does not make full use of the information of all examples. Therefore, we apply GHM to the classification loss function of RefineDet, so that the network can make full use of all examples and increase the weights of hard examples adaptively in the loss function to reduce the false alarms and the missing alarms. In addition, to achieve a better detection performance in SAR images with complex scenes, a multiscale feature attention module (MFAM) is embedded into the network. By applying channel and spatial attention mechanisms to the multiscale feature maps, the MFAM can highlight the significant information and suppress the interference caused by clutter. The extensive experimental results based on the measured SAR dataset verify the effectiveness of the proposed method.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9515178
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-duyuang-an SAR target detector.pdf'
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
