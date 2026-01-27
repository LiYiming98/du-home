---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Boosting Lightweight CNNs Through Network Pruning and Knowledge Distillation for SAR Target Recognition

# 作者信息
authors:
  - Zhen Wang
  - Lan Du
  - Yi Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-08-11T00:00:00Z'

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
abstract: 'Deep convolutional neural networks (CNNs) have yielded unusually brilliant results in synthetic aperture radar (SAR) target recognition. However, overparameterization is a widely-recognized property of deep CNNs, and most previous works excessively pursued high accuracy but neglected the requirement of model deployment in radar systems, i.e., small computations and low memory cost. Therefore, further research on lightweight CNNs for SAR target recognition is necessary. In this article, we devise an effective CNN with channel-wise attention mechanism for SAR target recognition and then compress the network structure and recover lightweight network performance through network pruning and knowledge distillation, respectively. The attention values produced by the network are utilized to evaluate the importance of convolution kernels, and unimportant kernels are pruned. In addition, a novel bridge connection based knowledge distillation method is proposed. Instead of directly mimicking the hidden layer output or artificially designing a function to extract the knowledge in hidden layers, bridge connections are introduced to distill internal knowledge via teacher network. Experiments are conducted on the moving and stationary target acquisition and recognition benchmark dataset. The proposed network has excellent generalization performance and reaches an accuracy of 99.46% on the classification of ten-class targets without any data augmentation. Furthermore, through the network pruning and knowledge distillation algorithm, we cut down 90% parameters of the proposed CNN while maintaining model performance.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9511826
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-wangzhen-boosting lightweight CNNs through.pdf'
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
