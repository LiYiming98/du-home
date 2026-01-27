---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Semi-Supervised SAR Target Detection Based on an Improved Faster R-CNN

# 作者信息
authors:
  - Liaolei Yao
  - Lan Du
  - Yuchen Guo



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-12-29T00:00:00Z'

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
abstract: 'In the remote sensing image processing field, the synthetic aperture radar (SAR) target-detection methods based on convolutional neural networks (CNNs) have gained remarkable performance relying on large-scale labeled data. However, it is hard to obtain many labeled SAR images. Semi-supervised learning is an effective way to address the issue of limited labels on SAR images because it uses unlabeled data. In this paper, we propose an improved faster regions with CNN features (R-CNN) method, with a decoding module and a domain-adaptation module called FDDA, for semi-supervised SAR target detection. In FDDA, the decoding module is adopted to reconstruct all the labeled and unlabeled samples. In this way, a large number of unlabeled SAR images can be utilized to help structure the latent space and learn the representative features of the SAR images, devoting attention to performance promotion. Moreover, the domain-adaptation module is further introduced to utilize the unlabeled SAR images to promote the discriminability of features with the assistance of the abundantly labeled optical remote sensing (ORS) images. Specifically, the transferable features between the ORS images and SAR images are learned to reduce the domain discrepancy via the mean embedding matching, and the knowledge of ORS images is transferred to the SAR images for target detection. Ultimately, the joint optimization of the detection loss, reconstruction, and domain adaptation constraints leads to the promising performance of the FDDA. The experimental results on the measured SAR image datasets and the ORS images dataset indicate that our method achieves superior SAR target detection performance with limited labeled SAR images.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/14/1/143
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-liaoleiyao-semi-supervised SAR target detection.pdf'
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
