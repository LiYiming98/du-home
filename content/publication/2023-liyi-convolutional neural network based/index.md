---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: 基于特征分解卷积神经网络的SAR图像目标检测方法

# 作者信息
authors:
  - 李毅
  - 杜兰
  - 杜宇昂



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2023-04-18T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '雷达学报'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: '真实场景的高分辨率合成孔径雷达(SAR)图像大多是复杂的，对于地物场景来说，其背景中存在草地、树木、道路和建筑物等杂波，这些复杂背景杂波使得传统SAR图像目标检测算法的结果包含大量虚警和漏警，严重影响了SAR目标检测性能。该文提出一种基于特征分解卷积神经网络(CNN)的SAR图像目标检测方法，该方法在特征提取模块对输入图像提取特征后，通过特征分解模块分解出鉴别特征和干扰特征，最后将鉴别特征输入到多尺度检测模块进行目标检测。特征分解后去除的干扰特征是对目标检测不利的部分，其中包括复杂背景杂波，而保留的鉴别特征是对目标检测有利的部分，其中包括感兴趣目标，从而有效降低虚警和漏警，提高SAR目标检测性能。该文所提方法在MiniSAR实测数据集和SAR飞机检测实测数据集(SADD)上的F1-score值分别为0.9357和0.9211，与不加特征分解模块的单步多框检测器相比，所提方法的F1-score值分别提升了0.0613和0.0639。基于实测数据集的实验结果证明了所提方法对复杂场景SAR图像进行目标检测的有效性。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://radars.ac.cn/article/doi/10.12000/JR23004
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2023-liyi-convolutional neural network based.pdf'
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
