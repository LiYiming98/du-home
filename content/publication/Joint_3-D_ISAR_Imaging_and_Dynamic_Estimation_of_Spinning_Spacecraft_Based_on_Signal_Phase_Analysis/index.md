---
# （重要修改） title：论文标题可以使用空格注意引号
title: 'Joint 3-D ISAR Imaging and Dynamic Estimation of Spinning Spacecraft Based on Signal Phase Analysis'

# （重要修改） 按照实际情况填写
authors:
  - Zhuowei Cao
  - Lan Du
  - Jian Chen
  - Haonan Guo

# （重要修改） 论文发表时间 只更改年月日
date: '2025-07-17T00:00:00Z'

#doi号
#doi: '10.1109/TAES.2025.3584322'

# （重要修改）同论文发表时间 只更改年月日
publishDate: '2025-07-17T00:00:00Z'

# 选填 1 或者 2 注意引号
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']


# 期刊/会议名称 要求全称
publication: 'IEEE Transactions on Geoscience and Remote Sensing'

# 留空
publication_short: ''

# （重要修改）文章摘要
abstract: Three-dimensional (3-D) geometry reconstruction and dynamic estimation of spinning spacecraft are crucial for space surveillance. Existing methods rely on interpreting 2-D inverse synthetic aperture radar (ISAR) images, which often suffer from image defocusing and scaling errors induced by target spin. To tackle this problem, we propose a joint 3-D ISAR imaging and dynamic estimation framework based on signal phase analysis, eliminating the need for prior 2-D imaging. After modeling the complex rotation of a spinning spacecraft relative to radar, we establish an overdetermined system of equations based on relationships between target parameters and cubic phase coefficients of radar echoes. Then, our two-step solution framework is organized as follows. First, we estimate cubic phase coefficients of the multicomponent signal through sparse representation (SR). To construct compact dictionaries for SR, we combine the coarse estimation and the phase order hierarchical processing (POHP) strategy to guide their design. Second, 3-D locations of scatterers, spin velocity, and direction of spin axis are estimated from the phase coefficients by solving the equation system. To ensure accurate and efficient solutions, we derive their iterative formulas using an alternating iterative strategy. With these formulas, 3-D ISAR imaging and dynamic estimation can be achieved directly. The effectiveness and superiority of our method are verified by experiments on simulated ISAR echoes.

# 这些都留空 不要删除
summary:  
tags:
featured: false

links:
  - name: Web Link
        #这里替换成IEEE网站的链接
    url: https://ieeexplore.ieee.org/document/11083635
        #这里替换成文件夹中pdf的相对路径 应为'./xxxxx.pdf' 注意引号和反斜杠
url_pdf: './Joint_3-D_ISAR_Imaging_and_Dynamic_Estimation_of_Spinning_Spacecraft_Based_on_Signal_Phase_Analysis.pdf'
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
