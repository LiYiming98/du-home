---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Vehicle target detection network in SAR images based on rectangle-invariant rotatable convolution

# 作者信息
authors:
  - Lu Li
  - Yuang Du
  - Lan Du



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-06-27T00:00:00Z'

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
abstract: 'In recent years, convolutional neural network (CNN)-based methods have been extensively explored for synthetic aperture radar (SAR) target detection. Nevertheless, the convolutional sampling locations of CNNs cannot accurately fit vehicle targets due to the fixed sampling mechanism in the convolutional kernel. In this paper, we focus on the vehicle target detection task in SAR images and propose a novel rectangle-invariant rotatable convolution (RIRConv) to determine more accurately the convolutional sampling locations for vehicle targets. Specifically, this paper considers the shape characteristic of vehicle targets in SAR images, which always retain a rectangular shape despite having varying sizes, aspect ratios, and rotation angles. The proposed RIRConv equips three additional learnable attribute parameters, namely, width, height, and angle attributes, to adaptively adjust the sampling locations in the convolutional kernel according to the targets. In addition, the RIRConv applies a modulation mechanism to focus on the sampling locations that significantly affect the output. Finally, the RIRConv is introduced into the single-shot multibox detector (SSD) to realize SAR vehicle target detection. In this way, the feature representation capability of SSD for vehicle targets can be enhanced, thus leading to higher detection performance. Notably, the proposed RIRConv is “plug-and-play” and can also be used with other existing advanced technologies to achieve higher detection performance. The experiments based on the measured miniSAR data validate the effectiveness of the proposed method.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/14/13/3086
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-lilu-vehicle target detection network.pdf'
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
