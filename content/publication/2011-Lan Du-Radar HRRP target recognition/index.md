---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: "Radar HRRP target recognition based on dynamic multi-task hidden Markov model"

# 作者信息
authors:
  - Lan Du
  - Penghui Wang
  - Hongwei Liu
  - Mian Pan
  - Zheng Bao



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2011-07-21T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 期刊/会议名称 （替换单引号内的XXX）
publication: '2011 IEEE RadarCon (RADAR)'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'A Bayesian multi-task model is developed for radar automatic target recognition (RATR) using high-resolution range profile (HRRP). The aspect-dependent HRRP sequence is modeled using a stick-breaking hidden Markov model (SB-HMM) with time-evolving transition probabilities, in which the spatial structure across range cells is described by the hidden Markov structure and the temporal (or orientational) dependence between HRRP samples is described by the time evolution of the transition probabilities. This framework imposes the belief that temporally proximate HRRPs are more likely to be drawn from similar HMMs, while also allowing for possible distant repetition or "innovation" associated with abrupt fluctuation in the HRRP sequence. In addition, as formulated the stick-breaking prior and multi-task learning (MTL) mechanism are employed to infer the number of hidden states in an HMM and learn the target dependent states collectively for all targets. The form of the proposed hierarchical model allows efficient variational Bayesian (VB) inference. The experimental results based on the measured HRRP data are compared with the MTL HMMs without time evolution and also some other existing statistical models.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/abstract/document/5960538
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2011-Lan Du-Radar HRRP target recognition.pdf'
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
