---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Target-attentional CNN for Radar Automatic Target Recognition with HRRP

# 作者信息
authors:
  - Jian Chen
  - Lan Du
  - Guanbo Guo
  - Linwei Yin
  - Di Wei



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2022-02-10T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Signal Processing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'In this paper, a target-attentional convolutional neural network (TACNN) combining the convolutional neural network (CNN) and attention mechanism is proposed for radar high-resolution range profile (HRRP) target recognition. The TACNN takes one-dimensional CNN (1-D CNN) as the feature extractor and has the capability to excavate abundant local structural features of data. However, the HRRP contains non-target areas, where the information is useless or even unfavorable. Furthermore, different parts of HRRP target regions should have differences in contribution to the recognition task. Therefore, it is an inadvisable approach that treats all local features alike and directly uses them for the subsequent target recognition, which is adopted by a lot of models, such as the conventional CNN. To tackle this problem, the TACNN introduces the attention mechanism on the basis of 1-D CNN. In detail, the constructed attention module adaptively assigns a weight to each local feature of HRRP so as to locate the target areas and meanwhile enhance the interest of model in valuable target information. Specially, the attention mechanism in TACNN is realized via a bidirectional gated recurrent unit (Bi-GRU) network, where the attention coefficients used for weighting up local features are generated with full consideration of sequential relationship among different regional features in HRRP. Therefore, the learned attention coefficients in our TACNN can better represent the importance of each local feature to the recognition task, ultimately beneficial for the discovery of target information with more discriminability. Experimental results on measured HRRP data show that the proposed model can get more effectiveness in target recognition than related methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.sciencedirect.com/science/article/pii/S0165168422000445
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2022-chenjian-target-attentional CNN for radar.pdf'
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
