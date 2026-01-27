---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Noise-Robust Classification of Ground Moving Targets Based on Time-Frequency Feature From Micro-Doppler Signature

# 作者信息
authors:
  - Lan Du
  - Yanyan Ma
  - Baoshuai Wang
  - Hongwei Liu



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2014-03-28T00:00:00Z'

# 2期刊论文；1会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Sensors Journal'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'A noise-robust classification method is proposed to
discriminate the moving vehicle and walking human via the timefrequency feature extracted from the micro-Doppler signature of
low resolution radar. Since the signal-to-noise ratio (SNR) directly
relates to the distance between the target and radar for a given
noise power and radar power, the denoising preprocessing is
usually required to increase the classification distance between
the target and radar in the real application. In this paper,
we extend the real-valued probabilistic principal component
analysis model to the complex-value domain, and develop the
complex probabilistic principal component analysis (CPPCA)
model for the complex-valued echoes from the ground moving
targets. Then, the denoising preprocessing is accomplished based
on signal reconstruction with CPPCA model, where we utilize
the Bayesian inference criterion (BIC) to adaptively select the
principal components. Compared with the existing CLEANbased noise reduction method, the CPPCA-BIC-based method
can work without SNR prior information. After denoising,
a 3-D time-frequency feature vector is extracted from the
denoised micro-Doppler signatures of the two kinds of ground
targets, and the classification is performed via support vector
machine classifier. In the experiments based on the measured
data, the proposed classification scheme shows good classification and denoising performances under the relatively low SNR
condition. The proposed method can also be applied to other
classification problems based on micro-Doppler effect.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/6780640
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Noise-Robust Classification of Ground Moving Targets.pdf'
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
