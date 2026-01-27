---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Adaptive Max-Margin One-Class Classifier for SAR Target Discrimination in Complex Scenes

# 作者信息
authors:
  - Leiyao Liao
  - Lan Du
  - Wei Zhang
  - Jian Chen



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-04-26T00:00:00Z'

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
abstract: 'Synthetic aperture radar (SAR) target discrimination is an important stage that distinguishes targets from clutters in the radar automatic target recognition field. However, in complex SAR scenes, the performance of some traditional discriminators will degrade. As an effective tool for one-class classification (OCC), the max-margin one-class classifier has attracted much attention for SAR target discrimination, as it can effectively reduce the impact of multiple clutters. However, the performance of the max-margin one-class classifier is very sensitive to the values of kernel parameters. To solve the problem, this paper proposes an adaptive max-margin one-class classifier for SAR target discrimination in complex scenes. In a max-margin one-class classifier with a suitable kernel parameter, the distance between a sample and classification boundary satisfies a certain geometric relationship, i.e., edge samples in input space are transformed to the region in the kernel space close to boundary, while interior samples in input space are transformed to the region in the kernel space far away from boundary. Therefore, we define the information entropy of samples in the kernel space to measure the distance between samples and classification boundary. To automatically obtain the optimal kernel parameter of the max-margin one-class classifier, the edge and interior samples in the input space are first selected, and then the parameter optimization is performed by minimizing information entropy of interior samples and simultaneously maximizing the information entropy of edge samples. Experimental results of the synthetic datasets and measured synthetic aperture radar (SAR) datasets validate the effectiveness of our method.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/14/9/2078
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-liaoleiyao-adaptive max-margin one-class classifier.pdf'
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
