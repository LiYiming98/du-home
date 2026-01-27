---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Semisupervised SAR Ship Detection Network via Scene Characteristic Learning

# 作者信息
authors:
  - Yuang Du
  - Lan Du
  - Yuchen Guo
  - Yu Shi



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2023-01-10T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Geoscience and Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'In recent years, target detection methods based on deep learning have achieved extensive development in synthetic aperture radar (SAR) ship detection. However, training such detectors requires target-level annotations of SAR images that are hard to be obtained in practice. To reduce the dependence of network training on expensive target-level annotations, we propose a novel semisupervised SAR ship detection network via scene characteristic learning. The proposed network focuses on utilizing the scene-level annotations of SAR images to improve the detection performance in the case of limited target-level annotations. Compared with the traditional fully supervised SAR ship detection network, the proposed network constructs a scene characteristic learning branch parallel with the detection branch. In the scene characteristic learning branch, a scene classification loss and a scene aggregation loss are designed to utilize the scene-level annotations. Under the constraint of these two losses, the feature extraction network can fully learn the scene characteristics of SAR images, thus enhancing its feature representation ability for ship targets and clutter. In addition, we propose a hierarchical test process from scene to target. After recognizing the scene types of input SAR images, we design different detection strategies for SAR images recognized as different scenes. The proposed test process can significantly reduce the inland and inshore false alarms, thus leading to higher detection performance. The experiments based on two measured SAR ship detection datasets demonstrate the effectiveness of the proposed method.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/10013741
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2023-duyuang-semisupervised SAR ship detection.pdf'
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
