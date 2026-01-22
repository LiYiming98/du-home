---
# （重要修改） title：论文标题可以使用空格注意引号
title: 'Class-Incremental SAR Ship Detection and Classification via Context-Robust Exemplar Replay and Multigranularity Knowledge Distillation'

# （重要修改） 按照实际情况填写
authors:
  - Yiming Li
  - Lan Du
  - Huayue Liu
  - Yuchen Guo

# （重要修改） 论文发表时间 只更改年月日
date: '2025-03-11T00:00:00Z'


# （重要修改）同论文发表时间 只更改年月日
publishDate: '2025-03-13T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称
publication: '电子与信息学报'

# 留空
publication_short: ''

# （重要修改）文章摘要
abstract: Class-incremental learning based on convolutional neural networks for synthetic aperture radar (SAR) targets has garnered wide attention recently. Unlike incremental SAR target classification, incremental SAR target detection and classification requires the model to detect and classify old targets while learning current ones, which is challenging due to the absence of old targets in the incremental large-scale data. To address the aforementioned issues, this article proposes a class-incremental SAR ship detection and classification method, which combines exemplar replay (ER) and knowledge distillation (KD) to facilitate the learning of the incremental model. Specifically, we propose a context-robust ER method to retain precise scene context between replayed old targets and clutter in the incremental data. By fully leveraging the scene characteristics of the ship targets, a context-robust ER method combines a local context-aware strategy with sea–land segmentation to pinpoint regions with the highest likelihood of being sea areas. Then, it replays exemplars within these regions, effectively reducing context-bias issues. In addition, a multigranularity KD method is introduced, which transfers the knowledge learned by the old detector to the current detector progressively. The multigranularity KD method combines an object mask strategy with spatial-channel attention mechanisms to constrain the current detector to focus on the most important information from the old detector. Experiments conducted on the SRSDD-v1.0 dataset indicate that our method achieves satisfactory performance in incremental detection and classification of SAR ships.
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/10925509
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
  - name: Public codes
    url: https://github.com/LiYiming98/CIL-for-SAR-ships
url_pdf: './李逸明-类增量检测识别.pdf'
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
