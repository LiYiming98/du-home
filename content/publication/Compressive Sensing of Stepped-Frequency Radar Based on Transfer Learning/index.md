---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Compressive Sensing of Stepped-Frequency Radar Based on Transfer Learning

# 作者信息
authors:
  - Danlei Xu
  - Lan Du
  - Hongwei Liu
  - Penghui Wang
  - Junkun Yan
  - Yulai Cong
  - Xun Han



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2015-04-10T00:00:00Z'

# 2期刊论文；1会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'It usually suffers from long observing time and
interference sensitivity when a radar transmits the high-range-resolution stepped-frequency chirp signal. Motivated by this, only
partial pulses of the stepped-frequency chirp are utilized. For the
obtained incomplete frequency data, a Bayesian model based on
transfer learning is proposed to reconstruct the corresponding
full-band frequency data. In the training phase, a complex beta
process factor analysis (CBPFA) model is utilized to statistically
model each aspect-frame from a set of given full-band frequency
data, whose probability density function (pdf) can be learned from
this CBPFA model. It is important to note that the numbers of
factors and dictionaries are automatically learned from the data.
The inference of CBPFA can be performed via the variational
Bayesian (VB) method. In the reconstruction phase for the incomplete frequency data that “related” to the training samples,
its corresponding full-band frequency data can be analytically
reconstructed via the compressive sensing (CS) method and
Bayesian criterion based on the transfer knowledge of the previous
pdfs learned from the training phase. About the “relatedness”
between each training frame and the incomplete test frequency
data, we utilize the frame condition distribution of incomplete test
frequency data to represent. The proposed method is validated on
the measured high range resolution (HRR) data.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/7084127
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Compressive Sensing of Stepped-Frequency Radar Based on Transfer Learning.pdf'
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
