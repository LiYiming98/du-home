---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: "Discriminative Mixture Variational Autoencoder for Semisupervised Classification"

# 作者信息
authors:
  - Jian Chen
  - Lan Du
  - Leiyao Liao



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2020-10-07T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Cybernetics'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'In this article, a deep probability model, called the discriminative mixture variational autoencoder (DMVAE), is developed for the feature extraction in semisupervised learning. The DMVAE consists of three parts: 1) the encoding; 2) decoding; and 3) classification modules. In the encoding module, the encoder projects the observation to the latent space, and then the latent representation is fed to the decoding part, which depicts the generative process from the hidden variable to data. In particular, the decoding module in our DMVAE partitions the observed dataset into some clusters via multiple decoders whose number is automatically determined via the Dirichlet process (DP) and learns a probability distribution for each cluster. Compared to the standard variational autoencoder (VAE) describing all data with a single probability function, the DMVAE has the capacity to give a more accurate description for observations, thus improving the characterization ability of the extracted features, especially for the data with complex distribution. Moreover, to obtain a discriminative latent space, the class labels of labeled data are introduced to restrict the feature learning via a softmax classifier, with which the minimum entropy of the predicted labels for the features from unlabeled data can also be guaranteed. Finally, the joint optimization of the marginal likelihood, label, and entropy constraints makes the DMVAE have higher classification confidence for unlabeled data while accurately classifying the labeled data, ultimately leading to better performance. Experiments on several benchmark datasets and the measured radar echo dataset show the advantages of our DMVAE-based semisupervised classification over other related methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9216561
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2020-chenjian-discriminative mixture variational autoencoder.pdf'
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
