---
# 请注意 任何参数（如摘要）值内出现的任何双引号（“）或反斜杠（如LaTeX\times）都应使用反斜杠（\）进行转义。例如，符号“和LaTeX text\times分别变为\”和\\times。有关详细信息，请参阅YAML或TOML文档。
#title：论文标题可以使用空格注意引号
title: 'Cross-Modal Distillation with Multi-Modal Fusion Networks for Remote Sensing Target Recognition Under Missing Modalities'
#按照实际情况填写
authors:
  - Huan Liu
  - Lan Du
  - Yu Shi
  - Yuchen Guo
  - Xin Liu
  - Hongxing Dang
#论文发表时间 只更改年月日
date: '2025-08-03T00:00:00Z'
#doi号
doi: '10.1109/IGARSS55030.2025.11243347'
#同论文发表时间 只更改年月日
publishDate: '2025-11-25T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 期刊/会议名称 要求全称
publication: ' IGARSS 2025 - 2025 IEEE International Geoscience and Remote Sensing Symposium'
# 留空
publication_short: ''
# 文章摘要
abstract: Multimodal learning has set off a research hotspot in the remote sensing field due to its powerful performance. Although the paired multimodal training data can be collected offline, some of the data may be missing due to the limitation of the environment or the equipment in practical applications. Therefore, it is of great significance to effectively utilize the complete modal information in the training phase to assist the inference under missing modalities in the testing phase. To address this challenge, we propose a feature fusion-guided cross-modal distillation network. In our method, we design the modal interaction attention fusion module to mine the complementary information from multimodal data, as a multimodal learning model in the complete data scenario. When missing modalities, we use a combined knowledge distillation method to perform cross-modal learning. This is achieved by transferring sample feature similarity relationships and aligning logits output distributions, thereby reducing the redundancy of cross-modal learning feature representations. Finally, we use decision fusion to combine modality-specific information to complete the model inference. The proposed method is experimentally validated on the UNICORN dataset, which can effectively improve the model recognition rate under missing modalities.
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: IEEE Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/11243347
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './cross modal distillation.pdf'
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
