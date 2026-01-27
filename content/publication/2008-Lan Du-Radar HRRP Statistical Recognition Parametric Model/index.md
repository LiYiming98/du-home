---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Radar HRRP Statistical Recognition: Parametric Model and Model Selection

# 作者信息
authors:
  - Lan Du
  - Hongwei Liu
  - Zheng Bao



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2008-05-31T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: "Statistical modeling for radar high-resolution range profile (HRRP) is a challenging task in radar HRRP statistical recognition. Theoretical analysis and experimental results show that elements in an HRRP sample are statistically correlated and non-Gaussian distributed. First, this paper introduces three joint-Gaussian models, i.e., subspace approximation model, probability principal components analysis (PPCA) model and factor analysis (FA) model, into radar HRRP statistical recognition. Due to the experimental results, we can have the conclusion that the jointly non-Gaussian distributed HRRP samples approximately follow the joint-Gaussian distribution described by FA model. Therefore, we can apply FA model to radar HRRP statistical recognition rather than a joint-Gaussian mixture model, e.g., PPCA mixture model or FA mixture model, which is a more accurate choice for modeling non-Gaussian distributed correlations in multidimensional data but with high learning complexity and large computation burden, and the difficulty in the statistical modeling for HRRP samples is largely reduced. Second, this paper concerns model selection of FA model in radar HRRP statistical recognition, in which there are two issues, i.e., the partition of target-aspect frames and the determination of the number of factors in each frame. Based on the Akaike information criterion (AIC) and the Bayes' information criterion (BIC), an iterated algorithm for model selection is proposed in this paper, which can automatically give the optimal aspect-frame boundaries and determine the optimal number of factors in each aspect-frame. The recognition experiments based on measured data show that the proposed adaptive partition approach can further improve the recognition performance with higher recognition efficiency."
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/4490100
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2008-Lan Du-Radar HRRP Statistical Recognition Parametric Model.pdf'
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
