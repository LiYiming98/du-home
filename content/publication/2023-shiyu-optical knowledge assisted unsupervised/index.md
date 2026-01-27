---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Optical knowledge assisted unsupervised cross-domain SAR target detection

# 作者信息
authors:
  - Yu Shi
  - Lan Du
  - Yuchen Guo 
  - Yuang Du



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2024-06-19T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IET International Radar Conference (IRC 2023)'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'Convolutional neural networks (CNNs) based synthetic aperture radar (SAR) target detection methods have garnered attention in recent years. However, labeled SAR images are scarce and expensive to acquire, making training CNNs challenging. In this paper, an unsupervised cross-domain SAR target detection method with the assistance of the knowledge of the labeled optical domain is proposed. Our method gradually improves the performance of the detector in the unlabeled SAR target domain from three stages. At the first stage, to reduce visual dissimilarity between optical and SAR images, the Optical-to-SAR generative adversarial network (GAN), namely Opt2SAR GAN with skip layer is proposed to generate labeled fake SAR images. At the second stage, the adversarial learning strategy is employed to make the detector learn the domain invariant features between the two domains. At the last stage, to alleviate domain-bias problem, we use pseudo-labels predicted by the detector of the second stage to learn more discriminative representations of the SAR domain. To further alleviate the impact of wrong pseudo-labels, we select confident pseudo-labels according the image uncertainty and proposal uncertainty. Experiments on two cross-domain detection datasets of vehicles and ships demonstrate the effectiveness of our method.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/10562568
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2023-shiyu-optical knowledge assisted unsupervised.pdf'
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
