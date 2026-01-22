---
# （重要修改） title：论文标题可以使用空格注意引号
title: '结合相似度预测和阈值自动求解的开集条件下毫米波雷达点云步态识别方法'

# （重要修改） 按照实际情况填写
authors:
  - 杜兰
  - 李逸明
  - 薛世鲲
  - 石钰
  - 陈健
  - 李真芳

# （重要修改） 论文发表时间 只更改年月日
date: '2025-05-19T00:00:00Z'


# （重要修改）同论文发表时间 只更改年月日
publishDate: '2025-09-01T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称
publication: '电子与信息学报'

# 留空
publication_short: ''

# （重要修改）文章摘要
abstract: 现有的雷达步态识别方法多局限于闭集设置，即假设测试阶段的所有身份类别均已包含在模板库中，不适用于库内已知身份类别和库外未知新身份类别共存的真实开放识别环境。针对非完备身份类别模板库条件下的步态识别问题，该文提出一种结合相似度预测和阈值自动求解的开集条件下毫米波雷达点云步态识别方法。在点云特征提取的基础上，结合对潜在未知类相似度得分分布的先验认知，设计了一种伪开放环境训练策略来学习相似度预测网络，提升相似度得分空间中已知类别与未知类别的鉴别性；最后，阈值自动求解模块通过极值理论对相似度得分的极值分布进行概率拟合，并通过最小虚警与漏检准则实现未知类拒判阈值的准确求解。基于实测毫米波雷达点云数据的实验结果表明了所提方法在开集条件下具有良好的识别稳健性。
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        #这里替换成IEEE网站的链接
    url: https://jeit.ac.cn/en/article/doi/10.11999/JEIT241034
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './李逸明-结合相似度阈值求解的毫米波点云.pdf'
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
