---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: "Point-wise discriminative auto-encoder with application on robust radar automatic target recognition"

# 作者信息
authors:
  - Chen Li
  - Lan Du
  - Sheng Deng
  - Yongguang Sun
  - Hongwei Liu



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '20YY-MM-DDT00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'Deep learning methods have a wide range of applications on various recognition problems for their ability to extract hierarchical features. However, most of the deep algorithms learn features from both the target area and the background area fulfilled with noise or clutter. In radar target recognition applications, the performance of applying deep learning methods directly on data with noise or clutter background is restricted because high-level features can be polluted by a significant amount of irrelevant patterns in the background. Therefore, a deep learning based model, point-wise discriminative auto-encoder, is proposed in this paper to extract noise and clutter robust features from the target area. We bind the original auto-encoder (AE) with a target area extraction net, which can learn the target area automatically from the raw data, to reduce the influence of the noise or clutter background. Moreover, we take advantage of the label information by adding a supervised constraint in our algorithm to help the target area extraction net learn the target area precisely and to extract discriminative high-level features. And then, our proposed method is applied to both high-resolution range profile (HRRP) data and synthetic aperture radar (SAR) images in radar automatic target recognition (RATR) problems. Experimental results on the measured HRRP data and SAR images show the advantages of our proposed method in real applications.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S0165168419304372
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2020-lichen-point-wise discriminative auto-encoder with.pdf'
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
