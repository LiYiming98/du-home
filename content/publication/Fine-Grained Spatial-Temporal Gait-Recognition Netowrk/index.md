---
# 论文名称，
title: Fine-Grained Spatial–Temporal Gait Recognition Network Based on Millimeter-Wave Radar Point Cloud

# 作者信息
authors:
  - Shikun Xue
  - Lan Du
  - Yu Shi
  - Xiaoyang Chen
  - Meng Xie


# （重要修改）同论文发表时间 只更改年月日!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
publishDate: '2023-11-21T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
publication: 'IEEE Transactions on Geoscience and Remote Sensing'

# 留空
publication_short: ''

# （重要修改）文章摘要!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
abstract: 'Radar-based gait recognition has gained wide attention recently for its ability to preserve privacy and adapt to low-light and poor-weather scenarios. Among different forms of input data, a radar point cloud is an appealing option as it captures not only the appearance signatures but also the motion signatures of the subject. For gait recognition, both appearance and motion are crucial signatures that can be represented by spatial features and temporal features, respectively. However, the spatial–temporal features extracted by existing radar point cloud-based methods are coarse-grained, leading to poor performance in realistic applications. To enhance the spatial–temporal feature representation ability of the radar point cloud-based method, in this article, we design a novel network to extract fine-grained spatial–temporal gait features from a millimeter-wave (mmWave) radar point cloud. For fine-grained spatial feature extraction, we apply a dual-stream feature extraction (DSFE) module to exploit the 3-D coordinates, intensity, and velocity information within the radar point cloud. After that, since each body part has its unique characteristics in the gait task, we also propose a probability-guided body-part partition (PGBP) module to split the radar point cloud into fine-grained spatial body parts. For fine-grained temporal feature extraction, a local–global temporal feature extraction (LGTE) module is used to further capture the temporal patterns of each body part. To evaluate the effectiveness of the proposed methods, we conduct extensive experiments with 90 subjects in various realistic settings, i.e., cross-view and cross-wearing conditions. The results demonstrate that our model achieves significant improvement over existing radar-based gait recognition methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
    url: https://ieeexplore.ieee.org/abstract/document/10368039
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Fine-Grained Spatial-Temporal Gait-Recognition Netowrk.pdf'
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
