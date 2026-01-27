---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Robust SAR Automatic Target Recognition Via Adversarial Learning

# 作者信息
authors:
  - Yuchen Guo
  - Lan Du
  - Di Wei
  - Chen Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2020-09-19T00:00:00Z'

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
abstract: 'The traditional denoising methods in noise robust synthetic aperture radar (SAR) automatic target recognition research are independent of the recognition model, which limits the robust recognition performance. In this article, we present a robust SAR automatic target recognition method via adversarial learning, which could integrate data denoising, feature extraction, and classification into a unified framework for joint learning. Different from the common recognition methods of directly inputting the SAR data into the classifiers, we add a dual-generative-adversarial-network (GAN) model between the SAR data and the classifier for data translation from a noise-polluted style to a relatively clean style to reduce the noise from SAR data. In order to ensure the target information in the SAR data can be retained during the data style translation, reconstruction constraint and label constraint are also used in the dual-GAN model. Then, the more reliable transferred SAR data are fed into the classifier. The parameters of the dual-GAN and classifier are learned through joint optimization in our method. Thus, the data separability is guaranteed in the process of denoising and feature extraction, which greatly improves the recognition performance of the method. In addition, our method can be easily extended to a semisupervised method by using different objective functions for labeled and unlabeled training data, which is more suitable for practical application. Experimental results on MSTAR dataset and Gotcha dataset show that our method can get the encouraging performance in the case of low signal-to-noise ratio and small labeled data size.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9264634
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2020-guoyuchen-robust SAR automatic target.pdf'
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
