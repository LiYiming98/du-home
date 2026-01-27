---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: SAR Target Detection Based on Domain Adaptive Faster R-CNN with Small Training Data Size

# 作者信息
authors:
  - Yuchen Guo
  - Lan Du
  - Guoxin Lyu



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-10-20T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'It is expensive and time-consuming to obtain a large number of labeled synthetic aperture radar (SAR) images. In the task of small training data size, the results of target detection on SAR images using deep network approaches are usually not ideal. In this study, considering that optical remote sensing images are much easier to be labeled than SAR images, we assume to have a large number of labeled optical remote sensing images and a small number of labeled SAR images with the similar scenes, propose to transfer knowledge from optical remote sensing images to SAR images, and develop a domain adaptive Faster R-CNN for SAR target detection with small training data size. In the proposed method, in order to make full use of the label information and realize more accurate domain adaptation knowledge transfer, an instance level domain adaptation constraint is used rather than feature level domain adaptation constraint. Specifically, generative adversarial network (GAN) constraint is applied as the domain adaptation constraint in the adaptation module after the proposals of Faster R-CNN to achieve instance level domain adaptation and learn the transferable features. The experimental results on the measured SAR image dataset show that the proposed method has higher detection accuracy in the task of SAR target detection with small training data size than the traditional Faster R-CNN.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/13/21/4202
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-guoyuchen-SAR target detection based.pdf'
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
