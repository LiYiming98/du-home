---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Class Factorized Variational Auto-encoder for Radar HRRP Target Recognition

# 作者信息
authors:
  - Jian Chen
  - Lan Du
  - Leiyao Liao



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2020-12-04T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '2020 IEEE Radar Conference (RadarConf20)'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: "In this paper, a class factorized variational auto-encoder (CFVAE) is developed for radar high-resolution range profile (HRRP) target recognition. The proposed model integrates the discriminative information into the deep statistical modeling of HRRP. In detail, the CFVAE utilizes an encoder to project all observations to the deep latent space and then separately defines the generative process from the latent features to observed data in each class, via the collection of specific class-decoders. Due to the stronger ability of each class-decoder to the description of observations in the corresponding class, the CFVAE model can directly assign a test sample into the class that corresponds to the decoder with the minimum reconstruction error, which avoids the mismatch of the extracted features and the back-end classifier. Meanwhile, compared to the traditional variational auto-encoder (VAE) describing the whole dataset with a single decoder, the proposed method has the capacity to give a more accurate description for all observations, thus beneficial to the improvement of features in characterization ability. Moreover, instead of imposing a fixed prior on the latent representations, our CFVAE model learns the conditional prior distribution based on the samples' labels, which further enhances the discrimination of the latent space. Finally, experiments on the measured HRRP dataset demonstrate the promising recognition performance of the proposed method."
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9266640
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2020-chenjian-class factorized variational quto-encoder.pdf'
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
