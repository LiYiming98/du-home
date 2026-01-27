---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: 基于多任务复数因子分析模型的雷达高分辨距离像识别方法

# 作者信息
authors:
  - 和 华 
  - 杜 兰
  - 徐丹蕾
  - 刘宏伟



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2015-09-01T00:00:00Z'

# 2期刊论文；1会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '电子与信息学报'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: '传统的高分辨距离像(HRRP)统计识别方法大部分只使用雷达目标高分辨回波的幅值信息且需要大量的训
练样本保证统计模型参数学习的精度。为了充分利用高分辨回波的相位信息，在雷达采样率有限、训练样本数不足
的条件下保证统计识别的性能，该文提出一种多任务学习(MTL)复数因子分析(CFA)模型，将数据描述推广到复数
域，将每个方位帧训练样本的统计建模视为单一的学习任务，各学习任务共享加载矩阵，利用贝塔伯努利
(Beta-Bernoulli)稀疏先验自适应地选择各任务需要的因子，完成多任务的共同学习。基于实测数据的识别实验显
示，与传统的单任务学习(STL)因子分析模型相比，该文提出的多任务因子分析模型具有更低的模型复杂度且在小
样本条件下可以显著提高识别性能。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://jeit.ac.cn/en/article/doi/10.11999/JEIT141591
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './基于多任务复数因子分析模型的雷达高分辨距离像识别方法.pdf'
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
