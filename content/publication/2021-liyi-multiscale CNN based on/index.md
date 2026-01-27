---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Multiscale CNN Based on Component Analysis for SAR ATR

# 作者信息
authors:
  - Yi Li
  - Lan Du
  - Wei Di



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-08-05T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'IEEE Transactions on Geoscience and Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'This article proposes a multiscale convolutional neural network (CNN) based on component analysis (CA-MCNN) for synthetic aperture radar (SAR) automatic target recognition (ATR). The component information of a target is robust to the local variations of the target, which is not made the best of by traditional CNN-based methods. For learning the component information, we use the attributed scattering centers (ASCs) extracted from the target echoes as the components of the target for SAR ATR, which divides the SAR target according to the geometric scattering types of ASCs and can not only make the division results more robust but also accurately characterize the electromagnetic scattering characteristics of the target. Since the global information provided by the whole image is also important for SAR ATR, CA-MCNN combines the global information with component information to learn a more efficient and robust target feature representation. In addition, considering that the feature maps of the shallower layer in CNN focus on local and fine-grained information while the feature maps in the deeper layer focus on global and coarse-grained information, we fuse the multiscale feature maps obtained from different layers to enhance the feature description ability. Extensive experiments conducted on the moving and stationary target acquisition and recognition (MSTAR) data set prove the superior performance of CA-MCNN.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/9507558
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-liyi-multiscale CNN based on.pdf'
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
