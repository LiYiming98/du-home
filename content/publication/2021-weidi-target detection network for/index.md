---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: Target Detection Network for SAR Images Based on Semi-Supervised Learning and Attention Mechanism

# 作者信息
authors:
  - Di Wei
  - Yuang DU
  - Lan Du
  - Lu Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-07-08T00:00:00Z'

# 1期刊论文；2会议论文
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# 期刊/会议名称 （替换单引号内的XXX）
publication: 'Remote Sensing'

# 留空
publication_short: ''

# 文章摘要XXX，注意冒号与摘要之间有空格。不要删除单引号'''
abstract: 'The existing Synthetic Aperture Radar (SAR) image target detection methods based on convolutional neural networks (CNNs) have achieved remarkable performance, but these methods require a large number of target-level labeled training samples to train the network. Moreover, some clutter is very similar to targets in SAR images with complex scenes, making the target detection task very difficult. Therefore, a SAR target detection network based on a semi-supervised learning and attention mechanism is proposed in this paper. Since the image-level label simply marks whether the image contains the target of interest or not, which is easier to be labeled than the target-level label, the proposed method uses a small number of target-level labeled training samples and a large number of image-level labeled training samples to train the network with a semi-supervised learning algorithm. The proposed network consists of a detection branch and a scene recognition branch with a feature extraction module and an attention module shared between these two branches. The feature extraction module can extract the deep features of the input SAR images, and the attention module can guide the network to focus on the target of interest while suppressing the clutter. During the semi-supervised learning process, the target-level labeled training samples will pass through the detection branch, while the image-level labeled training samples will pass through the scene recognition branch. During the test process, considering the help of global scene information in SAR images for detection, a novel coarse-to-fine detection procedure is proposed. After the coarse scene recognition determining whether the input SAR image contains the target of interest or not, the fine target detection is performed on the image that may contain the target. The experimental results based on the measured SAR dataset demonstrate that the proposed method can achieve better performance than the existing methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/13/14/2686
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-weidi-target detection network for.pdf'
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
