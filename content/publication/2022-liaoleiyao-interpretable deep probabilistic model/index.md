---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Interpretable Deep Probabilistic Model for HRR Radar Signal and its Application to Target Recognition

# 作者信息
authors:
  - Leiyao Liao
  - Lan Du
  - Jian Chen



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-03-17T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Journal of Selected Topics in Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: "With the advent of neural network, unprecedented advancements have been achieved in many tasks, including radar signal processing. However, a key disadvantage of the current methods is the black-box structure, which makes it hard to interpret or assess the hidden representations of data. In this paper, by combining the physical generative mechanism of the high range resolution (HRR) radar signal with neural network, we develop an interpretable deep probabilistic model to learn the latent features from HRR radar signals that can characterize the physical structure of targets. In detail, based on the radar target's scattering center model which describes the HRR radar signal as the summation of echoes from the scattering centers, a deep probabilistic model is constructed to depict the generative process from the scattering centers to observations, where the latent features comprise the locations and amplitudes of scattering centers. Considering that the locations of scattering centers are nearly invariable and the amplitudes of them are fluctuant for the signals within a small angular range, our model defines the shared locations and independent amplitudes of scattering centers for the signals in a small angular range, aiming to improve the robustness of interpretable feature extraction model. In addition, our model performs probabilistic inference on the posterior distribution of latent features with high preciseness. With the proposed model, we further design a recognition scheme based on the minimum reconstruction error criterion. Experiments on the measured HRR radar dataset validate the effectiveness of our model on learning interpretable features and superior recognition performance."
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9737394
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-liaoleiyao-interpretable deep probabilistic model.pdf'
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
