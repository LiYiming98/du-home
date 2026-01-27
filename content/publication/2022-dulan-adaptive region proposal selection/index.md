---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: XXX

# 作者信息
authors:
  - 杜兰
  - 王梓霖
  - 郭昱辰
  - 杜宇昂
  - 严俊坤



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-09-02T00:00:00Z'

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
abstract: '大场景合成孔径雷达(SAR)图像相对于通用光学图像，复杂背景杂波对目标特征提取影响更大，由于传统基于候选框的深度目标检测算法会在整张特征图上产生大量冗余候选框，因而在SAR图像复杂背景杂波影响下会产生大量的虚警，降低目标检测精度。针对该问题，该文基于Faster R-CNN检测模型，提出结合强化学习自适应候选框挑选的SAR目标检测方法。该方法能够通过强化学习自适应搜索特征图中可能含有目标的区域，并挑选搜索区域内的候选框继续进行分类、回归。通过准确搜索到含有目标的区域，可以减少复杂背景杂波的影响并减少传统强化学习应用于检测问题的计算量。所提方法利用强化学习序列决策的特点，能够根据图像信息通过强化学习迭代搜索自适应确定图像中可能含有目标的搜索区域的位置。同时，该方法通过在强化学习中使用距离约束，可以根据之前的搜索结果自适应调整下一次搜索区域的尺寸。基于实测数据的实验结果表明，所提方法能够提升传统深度学习目标检测方法的检测性能。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://radars.ac.cn/cn/article/doi/10.12000/JR22121
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-dulan-adaptive region proposal selection.pdf'
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
