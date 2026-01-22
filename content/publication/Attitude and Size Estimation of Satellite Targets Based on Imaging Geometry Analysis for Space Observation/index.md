---
# 请注意 任何参数（如摘要）值内出现的任何双引号（“）或反斜杠（如LaTeX\times）都应使用反斜杠（\）进行转义。例如，符号“和LaTeX text\times分别变为\”和\\times。有关详细信息，请参阅YAML或TOML文档。
#title：论文标题可以使用空格注意引号
title: 'Attitude and Size Estimation of Satellite Targets Based on Imaging Geometry Analysis for Space Observation'
#按照实际情况填写
authors:
  - Zhuowei Cao
  - Lan Du
  - Jian Chen
  - Shijia Zhu
#论文发表时间 只更改年月日
date: '2025-06-30T00:00:00Z'
#doi号
doi: '10.1109/TAES.2025.3584322'
#同论文发表时间 只更改年月日
publishDate: '2025-10-01T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 要求全称
publication: 'IEEE Transactions on Aerospace and Electronic Systems'
# 留空
publication_short: ''
# 文章摘要
abstract: Attitude and size estimation of satellite targets is crucial for space surveillance. Existing methods that utilize radar or optical images from ground-based sensors typically rely on the basic imaging projection model. These methods require long-time or multistation observation to provide sufficient views and struggle to achieve accurate estimations under conditions of small view differences. To mitigate reliance on extensive views, we propose a method based on imaging geometry analysis for space observation. In our work, five crucial properties about the imaging geometry of rectangular solar panels are explored. Compared with the basic projection model, these properties impose additional constraints on the estimation process, thereby decreasing estimation errors by approximately 50% under limited observation conditions. Then, guided by these properties, we establish an over-determined system of equations to estimate two side vectors of the rectangle from their projections in images. To solve this complex system, the coarse estimation with a weighting strategy is conducted to decouple the system into linear subsystems, and these subsystems are solved by an Alternating Iterative Reweighted Least Square algorithm. The accuracy, real-time performance, and noise robustness of our method are demonstrated by experiments under various observation conditions.
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: IEEE Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/11059756
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Attitude and Size Estimation of Satellite Targets Based on Imaging Geometry Analysis for Space Observation.pdf'
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
