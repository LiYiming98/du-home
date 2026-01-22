---
# （重要修改） title：论文标题可以使用空格注意引号
title: 'Open-Set Domain Adaptation via Adaptive Separation and Two-Level Alignment With Application in SAR Target Recognition'

# （重要修改） 按照实际情况填写
authors:
  - Yuchen Guo
  - Bin Yang
  - Lan Du
  - Jian Chen

# （重要修改） 论文发表时间 只更改年月日
date: '2025-09-29T00:00:00Z'


# （重要修改）同论文发表时间 只更改年月日
publishDate: '2025-09-29T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称
publication: 'IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing'

# 留空
publication_short: ''

# （重要修改）文章摘要
abstract: Open-set domain adaptation (OSDA) recognition assumes distribution shifts between labeled source domain data and unlabeled target domain data, with the target domain containing additional unknown class. The goal of OSDA recognition is to classify the known classes and identify the unknown class in target domain. Typical OSDA recognition studies first separate known and unknown classes in the target domain, then align shared known classes between source and target domains, but still face the issues of insufficient separation and negative alignment due to the confusion between unknown and known classes in the target domain. To address these challenges, this article proposes an OSDA recognition method via adaptive separation and two-level alignment (ASTA), and applies it to synthetic aperture radar target recognition. In the separation phase, to achieve precise separation of known and unknown class targets in the target domain and minimize the influence of unknown targets for knowledge transfer in the alignment phase, the proposed adaptive separation module constructs dynamically adjusted separation thresholds for different batches. In the alignment phase, to accurately transfer the classification knowledge from the source domain, this article introduces the multilevel alignment framework from closed-set domain adaptation, achieving cross-domain knowledge transfer at both domain level and class level. In particular, to ensure precise transfer of known class classification knowledge at the class-level alignment, the distance between cross-domain prototypes (constructed by prototype network) of the same class is minimized. To mitigate the negative impact of unknown class targets (missed during the separation phase) on target domain prototype construction, a prototype-based pseudolabel filtering strategy and a prototype construction loss weighting mechanism are proposed. The OSDA recognition results on the SAMPLE and Office-31 datasets demonstrate that ASTA achieves SOTA performance, proving its superiority.
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/11183838
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './paper.pdf'
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
