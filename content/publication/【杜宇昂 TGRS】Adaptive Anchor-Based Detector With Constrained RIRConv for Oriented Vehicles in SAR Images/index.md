---
# （重要修改） title：论文标题可以使用空格注意引号
title: 'UTM-YOLOX_Unknown_Target_Mining-Based_Open-Set_SAR_Ship_Detection_and_Classification'

# （重要修改） 按照实际情况填写
authors:
  - Yiming Li
  - Lan Du
  - Yuchen Guo
  - Hongyang Ma

# （重要修改） 论文发表时间 只更改年月日
date: '2025-10-20T00:00:00Z'


# （重要修改）同论文发表时间 只更改年月日
publishDate: '2025-10-20T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称
publication: 'IEEE Geoscience and Remote Sensing Letters'

# 留空
publication_short: ''

# （重要修改）文章摘要
abstract: Existing synthetic aperture radar (SAR) ship detection
and classification methods based on deep learning have
achieved notable performance under the close-set assumptions.
However, SAR object detection and classification tasks inherently
operate in open-set scenarios, which naturally involve the
potential presence of unknown noncooperative targets. Closed-set
methods cannot identify these unknown targets, often misclassifying
them as known classes or background, leading to significant
errors. Therefore, this letter proposes an unknown-target miningbased
open-set SAR ship detection and classification method
UTM-YOLOX, which preserves the performance for known
targets while enhancing the ability to detect and identify
unknown targets. First, class-agnostic localization quality estimation
(CLQE) is utilized in the regression heads of YOLOX
to improve the detection of unknown targets. Unlike binary
foreground-background classification, CLQE focuses on learning
the quality of target localization, providing richer information
for target detection. Second, an open-set classifier (OSC) is
proposed for classification heads of YOLOX to identify the
unknown targets and known classes, which includes unknown
class discriminant learning (UCDL) and contrastive clustering
learning (C2L). UCDL utilizes the detected proposals of suspected
unknown targets into the training of the OSC, enabling the model
to eectively identify unknown targets, while C2L is utilized to
improve the discriminative ability between known and unknown
targets. Experiments on SRSDD-v1.0 demonstrate that UTMYOLOX
achieves satisfactory performance. The code is available
at https://github.com/LiYiming98/UTM-YOLOX
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/11208641
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './【李逸明 GRLS】UTM-YOLOX_Unknown_Target_Mining-Based_Open-Set_SAR_Ship_Detection_and_Classification.pdf'
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
