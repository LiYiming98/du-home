---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Label constrained convolutional factor analysis for classification with limited training samples

# 作者信息
authors:
  - Jian Chen
  - Lan Du
  - Yuchen Guo



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-01-12T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Information Sciences'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'This paper mainly addresses the statistical classification robust to small training data size. We develop a label constrained convolutional factor analysis (LCCFA) model, which unifies the factor analysis (FA), convolution operation and supervised learning. In the LCCFA model, each dictionary atom is used as a small-sized convolution kernel with the goal of learning the observations’ basic structures, which have highly shared characteristics among all observed data. This property enables the proposed method to describe data with fewer dictionary atoms than the FA model and reduces the model complexity. Consequently, the classification performance of the LCCFA model can be improved in the case of limited training samples. Meanwhile, the proposed model also projects the weight vectors of dictionary atoms to their class labels to constrain the learning of parameters. The difference in weight vectors from different classes increases due to the label constraint, thereby offering the potential to enhance the inter-class separability of statistical models. Additionally, the efficient parameter estimation is implemented via variational Bayesian (VB) algorithm. Experimental results on several benchmark datasets and measured radar high-resolution range profile (HRRP) data show that our method outperforms other related models in terms of small sample classification.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S0020025520308161
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-chenjian-label constrained convolutional factor.pdf'
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
