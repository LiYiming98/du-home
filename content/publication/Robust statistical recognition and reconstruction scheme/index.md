---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Robust statistical recognition and reconstruction scheme based on hierarchical Bayesian learning of HRR radar target signal

# 作者信息
authors:
  - Lan Du
  - Penghui Wang
  - Lei Zhang
  - Hua He
  - Hongwei Liu



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2015-08-15T00:00:00Z'

# 2期刊论文；1会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Expert Systems with Applications'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'A hierarchical Bayesian model is developed to characterize the complex-valued high range resolution
(HRR) radar target signal, motivated by the problem of radar automatic target recognition (RATR) robust
to low signal-to-noise ratio (SNR) or narrowband interference. Here we assume a sparseness-promoting
prior on the complex echoes and a Markov dependency for the location of the dominant scattering center
between consecutive HRR signals. The number of the dominant scattering centers can be automatically
determined, while the posterior distributions of their complex coefficients and locations can be inferred
via such Bayesian model. In the training stage, based on the proposed Bayesian model, the statistical
aspect-frame template can be learned for HRR complex training samples from each target-aspect sector
under high SNR and without any interference. Considering the low SNR or narrowband interference problem for a test sample, the aspect-frame templates can be updated to make a robust recognition decision
for the noised and interfered test sample. Simultaneously, the test sample can be denoised and recovered
via the analytically posterior estimation for the reconstruction, which is referred to as the statistical compressive sensing (CS) inversion. In contrast to the traditional CS methods that only utilize the underlying
sparse property of a measurement (here a measurement is a test sample), our statistical CS inversion also
exploits the statistical information of the training samples, which are under high SNR and without any
interference. Therefore, the better recognition and reconstruction performances can be obtained via
our method. Efficient inference is performed via variational Bayesian (VB) for the proposed Bayesian
model. To validate the formulation, we present our experimental results on the measured HRR dataset,
with comparisons to some state-of-the-art methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S0957417415002237
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Robust statistical recognition and reconstruction scheme.pdf'
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
