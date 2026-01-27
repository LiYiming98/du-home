---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: "基于半监督学习的SAR目标检测网络"

# 作者信息
authors:
  - 杜兰
  - 魏迪
  - 李璐
  - 郭昱辰



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2019-12-09T00:00:00Z'

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
abstract: '现有的基于卷积神经网络(CNN)的合成孔径雷达(SAR)图像目标检测算法依赖于大量切片级标记的样本，然而对SAR图像进行切片级标记需要耗费大量的人力和物力。相对于切片级标记，仅标记图像中是否含有目标的图像级标记较为容易。该文利用少量切片级标记的样本和大量图像级标记的样本，提出一种基于卷积神经网络的半监督SAR图像目标检测方法。该方法的目标检测网络由候选区域提取网络和检测网络组成。半监督训练过程中，首先使用切片级标记的样本训练目标检测网络，训练收敛后输出的候选切片构成候选区域集；然后将图像级标记的杂波样本输入网络，将输出的负切片加入候选区域集；接着将图像级标记的目标样本也输入网络，对输出结果中的正负切片进行挑选并加入候选区域集；最后使用更新后的候选区域集训练检测网络。更新候选区域集和训练检测网络交替迭代直至收敛。基于实测数据的实验结果证明，所提方法的性能与使用全部样本进行切片级标记的全监督方法的性能相差不大。'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.jeit.ac.cn/article/doi/10.11999/JEIT190783
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2020-dulan-SAR target detection network.pdf'
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
