---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Two-Stream Deep Fusion Network Based on VAE and CNN for Synthetic Aperture Radar Target Recognition

# 作者信息
authors:
  - Lan Du
  - Lu Li
  - Yuchen Guo
  - Yan Wang
  - Ke Ren
  - Jian Chen



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-10-09T00:00:00Z'

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
abstract: 'Usually radar target recognition methods only use a single type of high-resolution radar signal, e.g., high-resolution range profile (HRRP) or synthetic aperture radar (SAR) images. In fact, in the SAR imaging procedure, we can simultaneously obtain both the HRRP data and the corresponding SAR image, as the information contained within them is not exactly the same. Although the information contained in the HRRP data and the SAR image are not exactly the same, both are important for radar target recognition. Therefore, in this paper, we propose a novel end-to-end two stream fusion network to make full use of the different characteristics obtained from modeling HRRP data and SAR images, respectively, for SAR target recognition. The proposed fusion network contains two separated streams in the feature extraction stage, one of which takes advantage of a variational auto-encoder (VAE) network to acquire the latent probabilistic distribution characteristic from the HRRP data, and the other uses a lightweight convolutional neural network, LightNet, to extract the 2D visual structure characteristics based on SAR images. Following the feature extraction stage, a fusion module is utilized to integrate the latent probabilistic distribution characteristic and the structure characteristic for the reflecting target information more comprehensively and sufficiently. The main contribution of the proposed method consists of two parts: (1) different characteristics from the HRRP data and the SAR image can be used effectively for SAR target recognition, and (2) an attention weight vector is used in the fusion module to adaptively integrate the different characteristics from the two sub-networks. The experimental results of our method on the HRRP data and SAR images of the MSTAR and civilian vehicle datasets obtained improvements of at least 0.96 and 2.16%, respectively, on recognition rates, compared with current SAR target recognition methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/13/20/4021
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-dulan-two-stream deep fusion network.pdf'
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
