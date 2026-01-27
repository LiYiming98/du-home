---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Mixture factor analysis with distance metric constraint for dimensionality reduction

# 作者信息
authors:
  - Jian Chen
  - Leiyao Liao
  - Wei Zhang
  - Lan Du



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-07-30T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Pattern Recognition'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'Dimensionality reduction (DR) is a key preprocessing stage in high-dimensional data classification. Traditional linear DR algorithms, e.g., Linear Discriminant Analysis, transform the original data into a low-dimensional subspace with a linear transformation matrix. However, these methods cannot handle complex nonlinearly separable data. Although some nonlinear DR methods, e.g., Locally Linear Embedding, are proposed to solve this problem, most of them are unsupervised, which only focus on the data structure hidden in the original high-dimensional space, rather than maximizing the inter-class separability of the transformed data, thus reducing the classification accuracy. To tackle this challenge, a novel supervised nonlinear DR algorithm, distance metric restricted mixture factor analysis (DMR-MFA), is proposed for high-dimensional data classification. In DMR-MFA, the original data is divided into several clusters, and the generation of original data in each cluster is described via a factor analysis model. Meanwhile, the distance metric constraint (DMC) is used for maximizing the separability of transformed low-dimensional data from different classes. Moreover, the optimal model parameters are learned via the joint optimization of log-likelihood function and DMC loss function, which makes the DMR-MFA possible to obtain the more separable low-dimensional embeddings while accurately describing the original data. Experimental results on synthetic data, benchmark datasets and high-resolution range profile data demonstrate that our method can handle nonlinearly separable data and improves the classification accuracy of data with high dimensionality.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S0031320321003435
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-chenjian-mixture factor analysis with.pdf'
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
