---
# 论文完整标题XXX，注意冒号与论文完整标题之间有空格
title: A Noise Robust Micro-Range Estimation Method for Precession Cone-Shaped Targets

# 作者信息
authors:
  - Zhenyu Zhuo
  - Yu Zhou
  - Lan Du
  - Ke Ren
  - Yi Li



# 论文发表时间，只修改年月日，T00:00:00Z保持不变
publishDate: '2021-05-07T00:00:00Z'

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
abstract: 'The estimation of micro-Range (m-R) is important for micro-motion feature extraction and imaging, which provides significant supports for the classification of a precession cone-shaped target. Under low signal-to-noise ratio (SNR) circumstances, the modified Kalman filter (MKF) will obtain broken segments rather than complete m-R tracks due to missing trajectories, and the performance of the MKF is restricted by unknown noise covariance. To solve these problems, a noise-robust m-R estimation method, which combines the adaptive Kalman filter (AKF) and the random sample consensus (RANSAC) algorithm, is proposed in this paper. The AKF, where the noise covariance is not required for the estimation of the state vector, is applied to associate m-R trajectories for higher estimation accuracy and lower wrong association probability. Due to missing trajectories, several associated segments which are parts of the m-R tracks can be obtained by the AKF. Then, the RANSAC algorithm is utilized to associate the segments and the complete m-R tracks can be obtained. Compared with the MKF, the proposed method can obtain complete m-R tracks instead of several segments, and avoids the influence of unknown noise covariance under low SNR circumstances. Experimental results based on electromagnetic simulation data demonstrate that the proposed method is more precise and robust compared with traditional methods.'
# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        # 这里替换成IEEE网站的链接
    url: https://www.mdpi.com/2072-4292/13/9/1820
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './2021-zhuozhenyu-a noise robust micro-range.pdf'
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
