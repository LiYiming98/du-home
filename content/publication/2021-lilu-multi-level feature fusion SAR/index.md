---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: 基于深度森林的多级特征融合SAR目标识别

# 作者信息
authors:
  - 李璐
  - 杜兰
  - 何浩男
  - 李晨
  - 邓盛



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2020-12-21T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '电子与信息学报'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: '大多数传统的合成孔径雷达(SAR)目标识别方法仅仅使用了单一的幅度特征，但是由于斑点噪声的存在，仅仅使用幅度特征会限制识别的性能。为了进一步提高SAR目标识别的性能，该文提出了一个基于深度森林的多级特征融合SAR目标识别方法。首先，在特征提取阶段，提取了多级幅度特征和多级密集尺度不变特征变换(Dense-SIFT)特征。幅度特征反映了目标反射强度，Dense-SIFT特征描述了目标的结构特征。而多级特征可以从局部到全局表征目标。随后，为了更完整、充分地反映SAR目标信息，借鉴深度森林的思想对多级幅度特征和多级Dense-SIFT特征进行联合利用。一方面通过堆叠的方式不断将多级幅度特征和多级Dense-SIFT特征进行融合，另一方面通过逐层的特征变换挖掘深层信息。最后利用得到的深层融合特征对目标进行识别任务。该文在MSTAR数据集上进行对比实验，实验结果表明所提算法在性能方面取得了提升，且其性能对超参数设置具有一定的鲁棒性。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://jeit.ac.cn/cn/article/doi/10.11999/JEIT200685
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-lilu-multi-level feature fusion SAR.pdf'
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
